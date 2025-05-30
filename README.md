# AIgorism Website

## 概述
AIgorism是一个专注于国际贸易与物流的AI平台，提供AI数据助手和AI邮件助手两大核心服务。网站采用深色主题设计，使用Tailwind CSS框架，确保现代化和响应式的用户体验。

## 页面结构

### 核心页面
1. **index.html** - 网站主页，展示平台概述和核心服务
2. **ai-data-assistant.html** - AI数据助手产品详情页面
3. **ai-email-assistant.html** - AI邮件助手产品详情页面
4. **pricing.html** - 综合定价方案页面，包含所有产品的定价信息和常见问题
5. **blog.html** - 博客文章列表页面
6. **docs.html** - 帮助文档和支持页面
7. **about.html** - 公司介绍和团队信息
8. **login.html** - 用户登录页面
9. **register.html** - 用户注册页面

### 其他文件
- **features.html** - 详细功能展示页面（可选）
- **README.md** - 项目文档

## 导航结构

网站采用一致的平铺式导航结构，所有页面都包含相同的导航菜单：

- **首页** → index.html
- **AI数据助手** → ai-data-assistant.html  
- **AI邮件助手** → ai-email-assistant.html
- **定价** → pricing.html
- **博客** → blog.html
- **帮助文档** → docs.html
- **关于我们** → about.html
- **登录** → login.html
- **开始使用** → register.html

## 技术特性

### 设计主题
- 深色主题（深蓝灰色调）
- 现代化的卡片式布局
- 悬浮效果和平滑过渡动画

### 响应式设计
- 支持桌面端和移动端
- 移动端提供折叠式导航菜单
- 灵活的网格布局适配不同屏幕尺寸

### 交互功能
- 流畅的导航体验
- 当前页面高亮显示
- 移动端菜单切换功能
- 定价页面的标签页切换和月付/年付切换

## 最新更新

### 文件名英文化（Latest Update）
1. **文件重命名**：
   - 所有HTML文件名已更新为英文命名规范
   - 保持SEO友好的URL结构
   - 便于国际化部署和维护

2. **链接更新**：
   - 全站链接已自动更新为新的英文文件名
   - 保持导航的一致性和完整性
   - 确保所有内部链接正常工作

3. **定价页面功能**：
   - 月付/年付切换功能
   - 多产品标签页切换（AI数据助手、AI邮件助手、专业套件、API服务）
   - 常见问题折叠展开功能
   - 完整的移动端适配

### 定价页结构
定价页包含以下内容：
- AI数据助手定价方案（免费版、专业版、企业定制版）
- AI邮件助手定价方案（免费版、专业版、企业定制版）  
- AIgorism专业套件（组合优惠方案）
- API服务定价（按量付费）
- 常见问题解答部分

## 部署说明

### 文件结构
```
AIgorism网站/
├── index.html                    # 网站首页
├── ai-data-assistant.html        # AI数据助手产品页
├── ai-email-assistant.html       # AI邮件助手产品页
├── pricing.html                  # 定价页面
├── blog.html                     # 博客页面
├── docs.html                     # 文档中心
├── about.html                    # 关于我们
├── login.html                    # 登录页面
├── register.html                 # 注册页面
├── features.html                 # 功能特性页（可选）
└── README.md                     # 项目文档
```

### 依赖项
- Tailwind CSS（通过CDN加载）
- Google Fonts - Inter字体
- 现代浏览器支持（支持ES6语法）

### 启动方式
将所有HTML文件部署到Web服务器，通过index.html开始访问。确保所有文件在同一目录下以保证相对链接正常工作。

### GitHub Pages部署
项目已配置为GitHub Pages友好：
- 主页文件使用标准的index.html命名
- 所有链接使用相对路径
- 无需服务器端处理，纯静态网站

## 维护说明

### 导航更新
如需添加新页面或修改导航结构，需要在所有HTML文件中同时更新导航部分，确保一致性。

### 样式定制
每个页面都包含内联样式，可以根据需要进行个性化调整，同时保持整体风格的协调性。

### 内容更新
- 产品信息更新：修改对应的产品页面
- 定价调整：修改pricing.html中的价格信息
- 博客内容：在blog.html中添加新文章

## SEO优化

### URL结构
- 使用语义化的英文文件名
- 简洁明了的URL路径
- 便于搜索引擎索引

### 页面结构
- 每个页面都有清晰的HTML语义结构
- 适当的heading标签层级
- 响应式设计提升移动端搜索排名

网站已完全整合，所有页面功能正常，导航链接正确，适合生产环境部署。 