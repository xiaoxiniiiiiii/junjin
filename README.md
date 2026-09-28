# JUNJIN HOME

俊锦贸易有限公司的家居生活电商前端演示，使用 React + Vite 构建。

## Start

```bash
npm i
npm run dev
```

## Included

- 5 个商品类目，75 件商品，价格区间约 $19–$279
- 本地 AI 生成的 WebP 商品图集，每个商品使用独立网格单元，避免重复图片
- Add to Cart 自动打开侧边购物车
- Buy Now - $price 加入购物车并跳转 Checkout
- Checkout 页面包含 PayPal、Visa、信用卡选项图标
- About、Shipping、Tracking、Returns、Cancellation、Terms（17 部分）、Privacy、DMCA 页面
- `#admin` 前端演示后台入口

## Admin demo

- URL: `/#admin`
- Account: `admin@junjinhome.com`
- Password: `demo-only`

这是前端演示登录，不连接真实订单、支付或客户数据库。正式上线前应接入真实后台鉴权，并替换演示凭据。

## Company information

- 公司名：俊锦贸易有限公司
- Email：junjinshop@outlook.com
- Address：Room 2209, 22/F, Convention Plaza Office Tower, 1 Harbour Road, Wan Chai, Hong Kong
- 电话与注册号：用户未提供，页面未虚构填写

## Git upload rules

`.gitignore` 已排除 `node_modules`、`dist`、日志和本地环境文件；项目内 `public/assets/*.webp` 是网站需要提交的正式图片资源。
