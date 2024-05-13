# 基于SpringBoot+Vue的在线商城及后台管理系统

###### @author: Zemelee

本项目定位商家自建站，不同于淘宝京东等主流平台，本系统只包含一个商家，系统由商家自运营

在线演示地址: [商城前台](http://sugarblack.top)

#### 本项目一共三个分支，不同的分支代表不同系统

master 表示商城前端，mall-manager 表示商城后台前端，backend 表示后端，backend分支包括mysql数据库文件

前端首次运行前在终端执行命令： `npm install`

后端首次运行前请等待依赖加载完毕

**本项目从鼠标右键新建文件夹到正式部署上线以及后期维护**

**每一次 commit 的内容均由作者本人独立完成**

~~也可能借鉴了亿点点AI的建议:joy:~~

---

### 项目技术栈

![techs](/image/techs.png)

| 前端        | 商城后台     | 后端            |
|-----------|----------|---------------|
| vue3.x    | vue2.x   | springboot2.7 |
| axios     | axios    | express (ws)  |
| element+  | element+ | MySQL         |
| vite      | vue-cli  | maven         |
| i18n      | echarts  | mybatis       |
| vue3typed |          |               |
---
### 商城功能
- 用户端
  - 商品浏览、商品搜索、规格选择、购物车管理、优惠券、订单管理、用户反馈、AI对话、人工对话
- 管理员端
  - 数据统计、商品管理、用户管理、订单管理、优惠券管理

### 性能优化

- 图像64转码
- 图片懒加载
- 组件防抖

### 特色功能

- 调用 SparkDesk 大模型能力，实现网站智能客服
- 篡改 AI 对话记录，可诱导大模型回答敏感问题(意外发现官方bug)
- 采用 WebSocket 技术，实现网站人工客服
- 基于 I18n 实现网站中英文切换
- 密码均以 HASH 传输
- ...