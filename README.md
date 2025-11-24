<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>经典HTML小游戏合集 - README</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        
        header {
            background: linear-gradient(120deg, #2c3e50, #3498db);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto;
        }
        
        .content {
            padding: 40px;
        }
        
        .section {
            margin-bottom: 40px;
        }
        
        h2 {
            color: #2c3e50;
            font-size: 2rem;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid #3498db;
        }
        
        h3 {
            color: #34495e;
            font-size: 1.5rem;
            margin: 20px 0 15px 0;
        }
        
        p {
            margin-bottom: 15px;
            font-size: 1.1rem;
            color: #555;
        }
        
        .games-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }
        
        .game-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            border: 2px solid #eee;
        }
        
        .game-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
            border-color: #3498db;
        }
        
        .game-card h4 {
            color: #2980b9;
            font-size: 1.3rem;
            margin-bottom: 10px;
        }
        
        .features {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .features ul {
            padding-left: 20px;
        }
        
        .features li {
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .tech-item {
            background: #3498db;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
        }
        
        .instructions {
            background: #e8f4fd;
            padding: 20px;
            border-radius: 10px;
            border-left: 5px solid #3498db;
        }
        
        .instructions ol {
            padding-left: 20px;
            margin: 15px 0;
        }
        
        .instructions li {
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        .footer {
            text-align: center;
            padding: 30px;
            background: #2c3e50;
            color: white;
            margin-top: 20px;
            border-radius: 0 0 15px 15px;
        }
        
        .highlight {
            background: linear-gradient(120deg, #f6d365 0%, #fda085 100%);
            padding: 3px 6px;
            border-radius: 4px;
            font-weight: bold;
            color: #2c3e50;
        }
        
        a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        @media (max-width: 768px) {
            .games-grid {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .content {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🎮 经典HTML小游戏合集</h1>
            <p class="subtitle">16个纯HTML5实现的经典小游戏，无需安装，离线可玩</p>
        </header>
        
        <div class="content">
            <div class="section">
                <h2>🎯 项目介绍</h2>
                <p>这是一个包含16个经典小游戏的合集，所有游戏均使用纯HTML、CSS和JavaScript开发，无需任何外部依赖。游戏界面美观，操作流畅，适合在任何现代浏览器中运行。</p>
                
                <div class="features">
                    <h3>✨ 主要特性</h3>
                    <ul>
                        <li>✅ <strong>纯前端实现</strong> - 无需服务器支持，直接打开HTML文件即可游玩</li>
                        <li>✅ <strong>响应式设计</strong> - 适配各种屏幕尺寸，支持移动端游玩</li>
                        <li>✅ <strong>离线可玩</strong> - 所有游戏均可在无网络环境下运行</li>
                        <li>✅ <strong>丰富多样</strong> - 涵盖益智、动作、策略等多种游戏类型</li>
                        <li>✅ <strong>代码开源</strong> - 完全开源，可自由学习和修改</li>
                    </ul>
                </div>
            </div>
            
            <div class="section">
                <h2>🛠 技术栈</h2>
                <div class="tech-stack">
                    <div class="tech-item">HTML5</div>
                    <div class="tech-item">CSS3</div>
                    <div class="tech-item">JavaScript</div>
                    <div class="tech-item">Canvas API</div>
                    <div class="tech-item">LocalStorage</div>
                </div>
            </div>
            
            <div class="section">
                <h2>📋 游戏列表</h2>
                <div class="games-grid">
                    <div class="game-card">
                        <h4>🐍 贪吃蛇游戏</h4>
                        <p>经典贪吃蛇游戏，控制蛇移动吃食物，越吃越长。支持键盘方向键操作。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>💣 扫雷游戏</h4>
                        <p>传统扫雷游戏，左键揭开方块，右键标记地雷。考验你的逻辑推理能力。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>❌ 井字棋游戏</h4>
                        <p>经典双人对战游戏，轮流在3×3网格中放置X和O，先连成一线者获胜。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🔢 2048数字游戏</h4>
                        <p>滑动方块合并相同数字，最终合成2048方块。支持最高分记录。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🧩 拼图游戏</h4>
                        <p>经典数字拼图，移动方块使其按顺序排列。记录步数和时间。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🃏 记忆翻牌游戏</h4>
                        <p>翻牌配对游戏，找出所有相同图案的配对。训练你的记忆力。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>✊ 石头剪刀布</h4>
                        <p>与电脑进行猜拳对决，支持石头、剪刀、布三种选择。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🔢 数独游戏</h4>
                        <p>经典数字逻辑游戏，填充空格使每行、每列和每个3×3区域都包含1-9数字。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🔗 连连看游戏</h4>
                        <p>消除相同图案的游戏，通过不超过两个转弯的线连接相同图案。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>⚫ 五子棋游戏</h4>
                        <p>黑白双方轮流落子，率先在横、竖或斜方向连成五子者获胜。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🧱 打砖块游戏</h4>
                        <p>控制挡板反弹小球击碎砖块，防止球掉落。支持鼠标和触摸操作。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🦘 跳一跳游戏</h4>
                        <p>按住空格键蓄力，松开跳跃到平台上。考验你的精准度。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>StoryboardSegue 华容道游戏</h4>
                        <p>移动方块解谜游戏，将曹操方块移动到出口位置。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>📦 推箱子游戏</h4>
                        <p>推动箱子到指定目标位置，箱子只能推不能拉。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>✈️ 飞机大战游戏</h4>
                        <p>控制飞机射击敌机，避免被敌机撞击。支持方向键移动和空格键射击。</p>
                    </div>
                    
                    <div class="game-card">
                        <h4>🐍 贪食蛇进化版</h4>
                        <p>功能增强版贪吃蛇，包含加速、减速、生长、缩小等特殊道具。</p>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2>🚀 使用说明</h2>
                <div class="instructions">
                    <h3>快速开始</h3>
                    <ol>
                        <li>克隆或下载本仓库到本地</li>
                        <li>直接在浏览器中打开 <span class="highlight">index.html</span> 文件</li>
                        <li>选择想要游玩的游戏，点击"开始游戏"按钮</li>
                        <li>享受游戏乐趣！</li>
                    </ol>
                    
                    <h3>部署到服务器</h3>
                    <ol>
                        <li>将所有HTML文件上传到Web服务器</li>
                        <li>通过浏览器访问 <span class="highlight">index.html</span></li>
                        <li>推荐使用现代浏览器以获得最佳体验</li>
                    </ol>
                </div>
            </div>
            
            <div class="section">
                <h2>🤝 贡献</h2>
                <p>欢迎提交Issue和Pull Request来改进这个项目。如果你有新的游戏想法或发现了bug，请随时贡献代码。</p>
            </div>
            
            <div class="section">
                <h2>📄 许可证</h2>
                <p>本项目采用MIT许可证，详情请查看 <a href="LICENSE">LICENSE</a> 文件。</p>
            </div>
        </div>
        
        <div class="footer">
            <p>🎮 经典HTML小游戏合集 | 开源项目 | 持续更新中</p>
            <p>如果你喜欢这个项目，请给个Star支持一下！⭐</p>
        </div>
    </div>
</body>
</html>
