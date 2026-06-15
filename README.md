<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人介绍 - 资深设计师</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#2563eb',
                        secondary: '#64748b',
                        accent: '#f59e0b',
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
            .card-shadow {
                box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
            }
            .gradient-bg {
                background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
        <!-- 顶部导航 -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <span class="text-xl font-bold text-primary">个人简介</span>
                </div>
                <div class="flex items-center space-x-4">
                    <a href=" " class="text-gray-600 hover:text-primary transition-colors">关于我</a >
                    <a href="#skills" class="text-gray-600 hover:text-primary transition-colors">专业技能</a >
                    <a href="#experience" class="text-gray-600 hover:text-primary transition-colors">工作经历</a >
                    <a href="#contact" class="text-gray-600 hover:text-primary transition-colors">联系方式</a >
                </div>
            </div>
        </div>
    </nav>

    <!-- 英雄区域（含照片） -->
    <section class="gradient-bg py-16 md:py-24">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center gap-10">
                                                <!-- 个人照片 -->
                <div class="flex-shrink-0">
                    <div class="w-48 h-48 md:w-64 md:h-64 rounded-full overflow-hidden border-4 border-white card-shadow">
                        < img src="xiao.jpg" alt="个人照片" class="w-full h-full object-cover">
                    </div>
                </div>
                <!-- 个人信息 -->
                <div class="text-center md:text-left text-white">
                    <h1 class="text-4xl md:text-5xl font-bold mb-3 text-shadow">张明远</h1>
                    <p class="text-xl md:text-2xl mb-4 opacity-90">资深室内设计师 / 创意总监</p >
                    <p class="text-lg opacity-80 max-w-xl mb-6">
                        10年设计经验，专注于商业空间与住宅室内设计，擅长将艺术美学与实用功能完美融合
                    </p >
                    <div class="flex justify-center md:justify-start space-x-4">
                        <a href="#contact" class="bg-white text-primary px-6 py-2 rounded-full font-medium hover:bg-gray-100 transition-colors">联系我</a >
                        <a href="#experience" class="border-2 border-white text-white px-6 py-2 rounded-full font-medium hover:bg-white hover:text-primary transition-colors">查看作品</a >
                    </div>
                </div>
            </div>
        </div>
    </section>
        <!-- 关于我 -->
    <section id="about" class="py-16">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">关于我</h2>
            <div class="bg-white rounded-2xl p-8 card-shadow">
                <div class="grid md:grid-cols-2 gap-8">
                    <div>
                        <h3 class="text-xl font-semibold mb-4 text-primary">个人简介</h3>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            毕业于中央美术学院环境艺术设计专业，拥有10年室内设计行业经验。曾任职于多家知名设计事务所，参与过超过200个商业与住宅项目。
                        </p >
                        <p class="text-gray-600 leading-relaxed">
                            设计理念："设计不是简单的美学堆砌，而是对生活方式的深度理解与重塑。每一个空间都应该讲述属于它的独特故事。"
                        </p >
                    </div>
                    <div>
                        <h3 class="text-xl font-semibold mb-4 text-primary">基本信息</h3>
                        <ul class="space-y-3">
                            <li class="flex items-center"><i class="fa fa-briefcase text-accent w-6"></i><span class="text-gray-600 ml-2">工作年限：10年</span></li>
                            <li class="flex items-center"><i class="fa fa-graduation-cap text-accent w-6"></i><span class="text-gray-600 ml-2">学历：中央美术学院 硕士</span></li>
                            <li class="flex items-center"><i class="fa fa-map-marker text-accent w-6"></i><span class="text-gray-600 ml-2">所在地：北京市朝阳区</span></li>
                            <li class="flex items-center"><i class="fa fa-language text-accent w-6"></i><span class="text-gray-600 ml-2">语言：中文、英语、日语</span></li>
                            <li class="flex items-center"><i class="fa fa-certificate text-accent w-6"></i><span class="text-gray-600 ml-2">资质：国家一级注册建筑师</span></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 专业技能 -->
    <section id="skills" class="py-16 bg-gray-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">专业技能</h2>
            <div class="grid md:grid-cols-3 gap-6">
                <div class="bg-white rounded-xl p-6 card-shadow hover:transform hover:-translate-y-1 transition-transform">
                    <div class="w-12 h-12 bg-primary/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fa fa-paint-brush text-primary text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4">设计软件</h3>
                    <ul class="space-y-2">
                        <li class="flex items-center"><span class="w-2 h-2 bg-primary rounded-full mr-2"></span><span class="text-gray-600">AutoCAD / SketchUp</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-primary rounded-full mr-2"></span><span class="text-gray-600">3ds Max / V-Ray</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-primary rounded-full mr-2"></span><span class="text-gray-600">Photoshop / Illustrator</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-primary rounded-full mr-2"></span><span class="text-gray-600">Enscape / Lumion</span></li>
                    </ul>
                </div>
                <div class="bg-white rounded-xl p-6 card-shadow hover:transform hover:-translate-y-1 transition-transform">
                    <div class="w-12 h-12 bg-accent/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fa fa-lightbulb-o text-accent text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4">设计能力</h3>
                    <ul class="space-y-2">
                        <li class="flex items-center"><span class="w-2 h-2 bg-accent rounded-full mr-2"></span><span class="text-gray-600">空间规划与布局设计</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-accent rounded-full mr-2"></span><span class="text-gray-600">软装搭配与色彩方案</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-accent rounded-full mr-2"></span><span class="text-gray-600">灯光设计与材质选择</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-accent rounded-full mr-2"></span><span class="text-gray-600">施工图深化与现场指导</span></li>
                    </ul>
                </div>
                <div class="bg-white rounded-xl p-6 card-shadow hover:transform hover:-translate-y-1 transition-transform">
                    <div class="w-12 h-12 bg-green-500/10 rounded-lg flex items-center justify-center mb-4">
                        <i class="fa fa-tasks text-green-500 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-4">项目管理</h3>
                    <ul class="space-y-2">
                        <li class="flex items-center"><span class="w-2 h-2 bg-green-500 rounded-full mr-2"></span><span class="text-gray-600">项目预算与进度控制</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-green-500 rounded-full mr-2"></span><span class="text-gray-600">团队协作与沟通协调</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-green-500 rounded-full mr-2"></span><span class="text-gray-600">客户需求分析与对接</span></li>
                        <li class="flex items-center"><span class="w-2 h-2 bg-green-500 rounded-full mr-2"></span><span class="text-gray-600">施工质量监督与验收</span></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
        <!-- 工作经历 -->
    <section id="experience" class="py-16">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">工作经历</h2>
            <div class="space-y-8">
                <div class="bg-white rounded-xl p-6 card-shadow">
                    <div class="flex flex-col md:flex-row md:items-start gap-4">
                        <div class="flex-shrink-0 w-32">
                            <span class="text-sm font-medium text-primary bg-primary/10 px-3 py-1 rounded-full">2020 - 至今</span>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">创意总监</h3>
                            <p class="text-secondary mb-2">艺境空间设计事务所 · 北京</p >
                            <p class="text-gray-600 leading-relaxed">
                                负责公司整体设计方向把控，带领15人设计团队完成各类项目。主导完成北京国贸中心商业空间改造、上海外滩高端住宅项目等多个标志性作品。
                            </p >
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-6 card-shadow">
                    <div class="flex flex-col md:flex-row md:items-start gap-4">
                        <div class="flex-shrink-0 w-32">
                            <span class="text-sm font-medium text-primary bg-primary/10 px-3 py-1 rounded-full">2016 - 2020</span>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">资深室内设计师</h3>
                            <p class="text-secondary mb-2">集艾设计 · 上海</p >
                            <p class="text-gray-600 leading-relaxed">
                                独立负责大型项目的全流程设计，从概念方案到施工落地全程跟进。参与完成多个五星级酒店、高端售楼处项目，累计项目面积超过10万平方米。
                            </p >
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-6 card-shadow">
                    <div class="flex flex-col md:flex-row md:items-start gap-4">
                        <div class="flex-shrink-0 w-32">
                            <span class="text-sm font-medium text-primary bg-primary/10 px-3 py-1 rounded-full">2014 - 2016</span>
                        </div>
                        <div>
                            <h3 class="text-xl font-semibold text-gray-800">室内设计师</h3>
                            <p class="text-secondary mb-2">梁志天设计师有限公司 · 香港</p >
                            <p class="text-gray-600 leading-relaxed">
                                参与多个高端住宅与商业项目的设计工作，学习国际先进设计理念与方法。负责方案深化、施工图绘制、材料选型等具体工作。
                            </p >
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
        <!-- 联系方式 -->
    <section id="contact" class="py-16 bg-gray-800 text-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-center mb-12">联系方式</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-xl font-semibold mb-6">随时欢迎联系我</h3>
                    <p class="text-gray-300 mb-8 leading-relaxed">
                        如果您有设计需求或合作意向，欢迎通过以下方式与我取得联系。我会在24小时内回复您的消息。
                    </p >
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <div class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center mr-4">
                                <i class="fa fa-envelope text-primary"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-400">邮箱</p >
                                <p class="font-medium">zhangmingyuan@design.com</p >
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center mr-4">
                                <i class="fa fa-phone text-primary"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-400">电话</p >
                                <p class="font-medium">+86 138 0000 8888</p >
                            </div>
                        </div>
                        <div class="flex items-center">
                            <div class="w-10 h-10 bg-primary/20 rounded-full flex items-center justify-center mr-4">
                                <i class="fa fa-weixin text-primary"></i>
                            </div>
                            <div>
                                <p class="text-sm text-gray-400">微信</p >
                                <p class="font-medium">zhang_design</p >
                            </div>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="bg-gray-700 rounded-xl p-6">
                        <h3 class="text-xl font-semibold mb-6">发送消息</h3>
                        <form class="space-y-4">
                            <div><input type="text" placeholder="您的姓名" class="w-full px-4 py-3 bg-gray-600 border border-gray-500 rounded-lg focus:outline-none focus:border-primary text-white placeholder-gray-400"></div>
                            <div><input type="email" placeholder="您的邮箱" class="w-full px-4 py-3 bg-gray-600 border border-gray-500 rounded-lg focus:outline-none focus:border-primary text-white placeholder-gray-400"></div>
                            <div><textarea rows="4" placeholder="请输入您的留言..." class="w-full px-4 py-3 bg-gray-600 border border-gray-500 rounded-lg focus:outline-none focus:border-primary text-white placeholder-gray-400 resize-none"></textarea></div>
                            <button type="submit" class="w-full bg-primary hover:bg-primary/90 text-white font-medium py-3 rounded-lg transition-colors">发送消息</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 页脚 -->
    <footer class="bg-gray-900 py-8 text-center text-gray-400">
        <div class="max-w-6xl mx-auto px-4">
            <p>&copy; 2024 张明远设计工作室. 保留所有权利.</p >
            <div class="flex justify-center space-x-6 mt-4">
                <a href=" " class="hover:text-white transition-colors"><i class="fa fa-behance"></i></a >
                <a href="#" class="hover:text-white transition-colors"><i class="fa fa-pinterest"></i></a >
                <a href="#" class="hover:text-white transition-colors"><i class="fa fa-instagram"></i></a >
                <a href="#" class="hover:text-white transition-colors"><i class="fa fa-linkedin"></i></a >
            </div>
        </div>
    </footer>

    <!-- 平滑滚动脚本 -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
