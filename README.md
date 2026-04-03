# 宁波明锐新材料官网部署指南

## 🚀 快速部署到 Vercel

### 步骤 1: 准备文件
确保以下文件已准备就绪：
- `index.html` - 主页面
- `sitemap.xml` - 站点地图
- `package.json` - 项目配置

### 步骤 2: 安装 Vercel CLI
```bash
npm i -g vercel
```

### 步骤 3: 登录 Vercel
```bash
vercel login
```

### 步骤 4: 部署
```bash
cd mingrui-website
vercel --prod
```

### 步骤 5: 绑定自定义域名
1. 登录 Vercel Dashboard: https://vercel.com/dashboard
2. 选择项目 → Settings → Domains
3. 添加域名: `mingruixc.com`
4. 按提示配置 DNS 解析

## 📋 文件结构
```
mingrui-website/
├── index.html      # 主页面 (已生成)
├── sitemap.xml     # 站点地图 (已生成)
├── package.json    # 项目配置 (已生成)
└── README.md       # 本文件
```

## 🔒 SSL 证书
Vercel 自动提供免费的 SSL 证书，无需手动配置！

## 🌐 访问地址
- 部署后: `https://mingrui-plastic-website.vercel.app`
- 绑定域名后: `https://mingruixc.com`

## ⚡ 优势
- ✅ 免费部署
- ✅ 全球 CDN 加速
- ✅ 自动 SSL 证书
- ✅ 无需备案
- ✅ 自动 HTTPS 跳转
