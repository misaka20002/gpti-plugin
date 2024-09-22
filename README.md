
```
git clone https://github.com/misaka20002/gpti-plugin.git ./plugins/gpti-plugin
```

![gpti-plugin](https://socialify.git.ci/CikeyQi/gpti-plugin/image?description=1&font=Raleway&forks=1&issues=1&language=1&name=1&owner=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Auto)

<img decoding="async" align=right src="resources/readme/girl.png" width="35%">

# GPTI-PLUGIN🍅

- 一个适用于 [Yunzai 系列机器人框架](https://github.com/yhArcadia/Yunzai-Bot-plugins-index) 的 GPT 插件，无需令牌来访问 GPT 与 AI 绘画

- 使用 [gpti-js](https://github.com/yandricr/gpti-js) 作为依赖调用，**免费**使用所有模型，包括对话模型与绘画模型

- **使用中遇到问题请加 QQ 群咨询：[707331865](https://qm.qq.com/q/TXTIS9KhO2)**

> [!TIP]
> 那天在 NPM 翻找有没有什么有趣的依赖库，翻到了 [gpti-js](https://github.com/yandricr/gpti-js) 这个项目，发现他们家的模型真多，不用在机器人身上就可惜了，立马整了个插件出来

## 安装插件

#### 1. 克隆仓库

```
git clone https://github.com/misaka20002/gpti-plugin.git ./plugins/gpti-plugin
```

> [!NOTE]
> 如果你的网络环境较差，无法连接到 Github，可以使用 [GitHub Proxy](https://mirror.ghproxy.com/) 提供的文件代理加速下载服务
>
> ```
> git clone https://ghp.ci/https://github.com/misaka20002/gpti-plugin.git ./plugins/gpti-plugin
> ```

#### 2. 安装依赖

```
pnpm install --filter=gpti-plugin
```

## 插件配置

> [!WARNING]
> 非常不建议手动修改配置文件，本插件已兼容 [Guoba-plugin](https://github.com/guoba-yunzai/guoba-plugin) ，请使用锅巴插件对配置项进行修改

## 功能列表

请使用 `#gpti帮助` 获取完整帮助

- [x] ChatGPT
- [x] ChatGPT Web
- [x] Bing
- [x] LLaMA-2
- [x] DALL·E
- [x] DALL-E Mini
- [x] Prodia
- [x] Prodia Stable-Diffusion
- [x] Stable-Diffusion 1.5
- [x] Stable-Diffusion 2.1
- [x] EMI

## 常见问题

1. 请求报错？
   - 可能是 gpti-js 那边寄了，等他们修好就能继续用了

## 支持与贡献

如果你喜欢这个项目，请不妨点个 Star🌟，这是对开发者最大的动力， 当然，你可以对我 [爱发电](https://afdian.net/a/sumoqi) 赞助，呜咪~❤️

有意见或者建议也欢迎提交 [Issues](https://github.com/CikeyQi/gpti-plugin/issues) 和 [Pull requests](https://github.com/CikeyQi/gpti-plugin/pulls)。

## 相关项目

- [gpti-js](https://github.com/yandricr/gpti-js)：This package simplifies your interaction with various GPT models, removing the need for tokens or other methods to access GPT

## 许可证

本项目使用 [GNU AGPLv3](https://choosealicense.com/licenses/agpl-3.0/) 作为开源许可证。
