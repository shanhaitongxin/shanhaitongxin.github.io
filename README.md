# shanhaitongxin.github.io
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>联系我们</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft Yahei", sans-serif;
        }

        body {
            background-color: #f0f7ff;
            color: #333;
        }

        /* 头部标题 */
        .header {
            background-color: #1677ff;
            text-align: center;
            padding: 50px 20px;
            color: #fff;
        }

        .header h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        .header p {
            font-size: 16px;
            opacity: 0.9;
        }

        /* 容器 */
        .container {
            max-width: 1100px;
            margin: -40px auto 60px;
            padding: 0 20px;
        }

        .contact-wrap {
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(22, 119, 255, 0.15);
            padding: 40px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }

        /* 联系信息 */
        .contact-info h3 {
            color: #1677ff;
            font-size: 24px;
            margin-bottom: 25px;
            padding-bottom: 10px;
            border-bottom: 2px solid #e8f3ff;
        }

        .info-item {
            margin-bottom: 20px;
            font-size: 16px;
            line-height: 1.8;
        }

        .info-item strong {
            color: #1677ff;
            display: inline-block;
            width: 80px;
        }

        /* 表单样式 */
        .contact-form h3 {
            color: #1677ff;
            font-size: 24px;
            margin-bottom: 25px;
            padding-bottom: 10px;
            border-bottom: 2px solid #e8f3ff;
        }

        .form-item {
            margin-bottom: 18px;
        }

        .form-item input,
        .form-item textarea {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #cce4ff;
            border-radius: 6px;
            font-size: 15px;
            outline: none;
            transition: 0.3s;
        }

        .form-item input:focus,
        .form-item textarea:focus {
            border-color: #1677ff;
            box-shadow: 0 0 0 3px rgba(22, 119, 255, 0.2);
        }

        .form-item textarea {
            height: 120px;
            resize: none;
        }

        .submit-btn {
            width: 100%;
            padding: 13px;
            background-color: #1677ff;
            color: #fff;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }

        .submit-btn:hover {
            background-color: #0958d9;
        }

        /* 手机适配 */
        @media (max-width: 768px) {
            .contact-wrap {
                grid-template-columns: 1fr;
                padding: 25px;
            }
            .header h1 {
                font-size: 28px;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>联系我们</h1>
        <p>有任何问题，欢迎随时咨询</p >
    </div>

    <div class="container">
        <div class="contact-wrap">
            <!-- 左侧联系信息 -->
            <div class="contact-info">
                <h3>联系方式</h3>
                <div class="info-item">
                    <strong>地址：</strong>广东省乐昌市乐昌市第一中学八《2》班
                </div>
                <div class="info-item">
                    <strong>联系电话：</strong>13411146181
                </div>
                <div class="info-item">
                    <strong>电子邮箱：</strong>shanhaitongxin-24
                </div>
                <div class="info-item">
                    <strong>开放时间：</strong>周一至周五中午12：30
                </div>
                <div class="info-item">
                    <strong>注：</strong>在线留言维护中,请通过联系电话,邮箱或线下报名
            </div>

            <!-- 右侧留言表单 -->
            <div class="contact-form">
                <h3>在线留言</h3>
                <form>
                    <div class="form-item">
                        <input type="text" placeholder="请输入您的姓名">
                    </div>
                    <div class="form-item">
                        <input type="text" placeholder="请输入联系电话">
                    </div>
                    <div class="form-item">
                        <input type="email" placeholder="请输入邮箱地址">
                    </div>
                    <div class="form-item">
                        <textarea placeholder="请输入您的留言内容..."></textarea>
                    </div>
                    <button class="submit-btn">提交留言</button>
                </form>
            </div>
        </div>
    </div>
</body>
</html>
