# 🚀 快速部署指南

## 立即部署到公网

### 步骤1：准备文件
确保你的项目文件夹包含以下文件：
- ✅ index.html
- ✅ about.html  
- ✅ products.html
- ✅ equipment.html
- ✅ quality.html
- ✅ contact.html
- ✅ styles.css
- ✅ script.js
- ✅ images/ (文件夹，包含所有图片)

### 步骤2：选择部署方式

#### 🌟 推荐：GitHub Pages（免费，5分钟完成）

1. **注册GitHub账号**
   - 访问 https://github.com
   - 点击"Sign up"注册

2. **创建仓库**
   - 点击右上角"+" → "New repository"
   - Repository name: `你的用户名.github.io`
   - 选择"Public"
   - 点击"Create repository"

3. **上传文件**
   ```bash
   # 在项目文件夹中打开命令行
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/你的用户名/你的用户名.github.io.git
   git push -u origin main
   ```

4. **启用Pages**
   - 进入仓库 → Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - 点击"Save"

5. **访问网站**
   - 等待2-3分钟
   - 访问: `https://你的用户名.github.io`

#### 🎯 最简单：Netlify（免费，2分钟完成）

1. **注册Netlify**
   - 访问 https://netlify.com
   - 点击"Sign up"注册

2. **拖拽部署**
   - 登录后，直接将整个项目文件夹拖拽到部署区域
   - 自动生成网址

3. **完成**
   - 获得类似 `https://random-name.netlify.app` 的网址

#### ⚡ 最快速：Vercel（免费，1分钟完成）

1. **注册Vercel**
   - 访问 https://vercel.com
   - 使用GitHub账号登录

2. **导入项目**
   - 点击"New Project"
   - 选择你的GitHub仓库
   - 点击"Deploy"

3. **完成**
   - 自动部署并生成网址

### 步骤3：自定义域名（可选）

如果你有自己的域名：

1. **购买域名**
   - 阿里云、腾讯云、GoDaddy等

2. **设置DNS**
   - 添加CNAME记录指向你的部署平台

3. **绑定域名**
   - 在部署平台设置中添加自定义域名

## 🎉 部署完成！

你的企业官网现在已经可以公网访问了！

### 下一步：
1. **测试网站**：在不同设备上测试显示效果
2. **更新内容**：根据需要修改文字和图片
3. **SEO优化**：添加关键词和描述
4. **分享推广**：将网址分享给客户和合作伙伴

## 📞 需要帮助？

如果遇到问题，可以：
- 检查文件是否完整
- 确认图片路径正确
- 查看浏览器控制台错误信息
- 联系技术支持

---

**恭喜！你的企业官网已经成功上线！** 🎊 