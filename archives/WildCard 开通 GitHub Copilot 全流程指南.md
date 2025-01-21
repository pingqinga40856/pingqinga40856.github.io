
之前为了使用 GPT-4，我办理了一张 WildCard 虚拟卡。后来发现这张卡支持的服务越来越多。最近为了体验 GitHub Copilot（免费试用一个月），需要绑定一张信用卡，于是用这张虚拟卡完成了开通。以下是详细的开通过程记录。

---

## 什么是 GitHub Copilot？

GitHub Copilot 是由 GitHub 推出的一款人工智能编程助手，基于 OpenAI 的 GPT 模型开发，旨在帮助开发者更高效地编写代码。它可以理解编程语言的上下文，自动生成代码片段甚至完整的函数。Copilot 可作为插件直接集成到 VS Code、IntelliJ 等主流编辑器中，为开发者提供即时的代码建议。

### 主要功能

- **代码自动完成**：不仅能完成基础的代码补全任务，还能根据注释或部分代码生成复杂的代码块和算法实现。
- **编写测试**：通过简单描述测试目的，Copilot 可自动生成对应的测试代码，适用于快速单元测试场景。
- **支持多种语言**：支持包括 Python、Java、Go、Ruby、C++ 等多种编程语言。
- **编写文档**：帮助开发者生成代码的文档注释，加快文档编写过程，提升代码可读性。

### 工作原理

GitHub Copilot 使用了大规模的代码数据库，包括公开的源代码库和 GitHub 上托管的项目。通过机器学习模型的训练，它能够理解编程语言的语法和语义，从而在开发者编写代码时提供相应的建议。

---

## GitHub Copilot 开通过程

### 1. 注册 GitHub 账号

使用 Copilot 必须先注册一个 GitHub 账号。

### 2. 准备信用卡或虚拟卡

我使用的是 WildCard 办理的虚拟卡，具体办理流程可参考相关教程。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)

### 3. 进入 GitHub Copilot 页面

访问 [GitHub Copilot 设置页面](https://github.com/settings/copilot) 启用助手。

> **提示**：以下步骤需要使用网络工具，我选择的是香港节点，亲测可用。

### 4. 选择试用

新用户可免费试用 30 天。试用结束后若未取消订阅，将自动续费一个月。建议有条件的用户直接开通年卡。

![选择30天试用](https://i-blog.csdnimg.cn/blog_migrate/488d26c4afac6ef58e459b76007b7005.png)

### 5. 填写支付信息

认真填写虚拟卡的账单地址信息并保存。

![填写账单地址](https://i-blog.csdnimg.cn/blog_migrate/90b7e921d5f7cccf63e69e1e178f1e44.png)

### 6. 输入卡号

填写虚拟卡信息，包括卡号、过期时间和 CVV 码。

![填写卡号](https://i-blog.csdnimg.cn/blog_migrate/33429c6a151333773f4b9287fd33d328.png)

### 7. 确认支付信息

确认支付信息无误后提交。

![确认信息](https://i-blog.csdnimg.cn/blog_migrate/9f91166b19eabee3391fdf7fec317105.png)

### 8. 隐私协议

可以选择不让 GitHub 使用自己的代码段进行训练。

![隐私协议](https://i-blog.csdnimg.cn/blog_migrate/ff0459c49dbfe01b7469339e6a7d3f8a.png)

### 9. 开通成功

出现以下界面说明开通成功，建议按需安装插件。

![开通成功](https://i-blog.csdnimg.cn/blog_migrate/ccbfdf932eb7b1f620c1d9b6846238a9.png)

### 10. 预扣款

虚拟卡账单会显示预扣款 10 美元，几天后会退回。但需要注意的是，WildCard 会收取一定手续费。

![预扣款](https://i-blog.csdnimg.cn/blog_migrate/f161bd3b86c954ed302e3ac534c49209.png)  
![退款被扣钱](https://i-blog.csdnimg.cn/blog_migrate/b9e38811bad6aa9f68fcc6b177717896.png)

---

## 插件使用指南

以下以 IDEA 为例，展示如何使用 GitHub Copilot 插件，其他 IDE 同理。

### 1. 安装插件

依次点击 `File -> Settings -> Plugins -> Marketplace`，搜索 `GitHub Copilot`，点击 Install 安装并重启 IDEA。

![搜索插件](https://i-blog.csdnimg.cn/blog_migrate/f86c93a02eec7c9b9b807e71a6e7ecb1.png)

### 2. 登录插件账号

点击右下角插件图标，登录 GitHub，跳转到网页完成账号登录并授权。

![登录账号](https://i-blog.csdnimg.cn/blog_migrate/fc030a97fefa3232ee1f97065a70c2b8.png)  
![登录并授权成功](https://i-blog.csdnimg.cn/blog_migrate/dd4ce27726998f1b18291ef4ce1d7009.png)

### 3. 使用插件

体验 Chat 功能，通过对话形式快速获取代码建议。（需配置网络工具或代理）

![使用](https://i-blog.csdnimg.cn/blog_migrate/98cc9e7fa5ba76918864d0a970910075.png)

### 4. 编码测试

- **注释生成代码**  
  ![代码生成](https://i-blog.csdnimg.cn/blog_migrate/806cff2ad59cf8698ceaef19b7b81397.png)

- **解释代码**  
  ![代码解释](https://i-blog.csdnimg.cn/blog_migrate/d808c7bbef692692f64bf4da571bebf7.png)

- **代码改写**  
  ![代码改写](https://i-blog.csdnimg.cn/blog_migrate/2a6e5feb46ca22b20827b7f4a7baf726.png)

---

## 如何取消试用？

点击个人头像 -> Settings -> Billing and plans -> Plans and usage -> Add-ons -> Cancel trial。

![取消试用](https://i-blog.csdnimg.cn/blog_migrate/4577aa63b6c285fb64d998fd1836c05b.png)