
![Grasscutter](https://socialify.git.ci/woailulu/GenshinImpact-PrivateService/image?description=1&descriptionEditable=Liver%20is%20replaced%20by%20deer%0A%2F%2F%5C%5CGenshin%20Impact%20Private%20Service&font=Rokkitt&language=1&logo=https%3A%2F%2Fs2.loli.net%2F2023%2F10%2F29%2F2S7PfkaxUmvqeRo.jpg&name=1&owner=1&pattern=Formal%20Invitation&theme=Dark)


[简中](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/README.md) |
[繁中](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_zh-TW.md) | 
[FR](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_fr-FR.md) | 
[ES](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_es-ES.md) | 
[HE](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_HE.md) |
[RU](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_ru-RU.md) | 
[PL](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_pl-PL.md) | 
[ID](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_id-ID.md) | 
[KR](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_ko-KR.md) | 
[FIL/PH](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_fil-PH.md) | 
[NL](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_NL.md) | 
[JP](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_ja-JP.md) | 
[IT](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_it-IT.md) | 
[VI](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_vi-VN.md) | 
[हिंदी](https://github.com/woailulu/GenshinImpact-PrivateService/blob/%E9%87%8D%E7%82%B9/%E7%95%8C%E9%9D%A2/README_hn-IN.md)

**注意:** 我们始终欢迎项目的贡献者。但在做贡献之前，请仔细阅读我们的[代码规范](https://github.com/Grasscutters/Grasscutter/blob/stable/CONTRIBUTING.md)。

## 当前功能

* 登录
* 战斗
* 好友
* 传送
* 祈愿
* 多人游戏 *部分* 可用
* 从控制台生成魔物
* 背包功能（接收或升级物品、角色等）。
 
## 快速安装指南

**注意:** 如需帮助，请加v或q

### 快速开始（全自动）

- 获取Java 17：
- 获取MongoDB社区版
- 获取游戏4.0正式版 (如果你没有4.0的客户端，可以在这里找到）：https://github.com/MAnggiarMustofa/GI-Download-Library/blob/main/GenshinImpact/Client/4.0.0.md)

- 下载[最新的Cultivation版本]（使用以“.msi”为后缀的安装包）。
- 以管理员身份打开Culivation，按右上角的下载按钮。
- 点击“下载 Grasscutter 一体化”
- 点击右上角的齿轮
- 将游戏安装路径设置为你游戏所在的位置。
- 将自定义Java路径设置为`C:\Program Files\Java\jdk-17\bin\java.exe`
- 保持所有其它设置为默认值

- 点击“启动”按钮旁边的小按钮。
- 点击“启动”按钮。
- 随便想一个用户名登录，不需要密码。

### 构建

Grasscutter使用Gradle来处理依赖和构建。

**前置：**

- [Java SE Development Kits - 17]
- [Git]

##### Windows

```shell
git clone --recurse-submodules https://github.com/Grasscutters/Grasscutter.git
cd Grasscutter
.\gradlew.bat # 设置开发环境
.\gradlew jar # 编译
```

##### Linux（GNU）

```bash
git clone --recurse-submodules https://github.com/Grasscutters/Grasscutter.git
cd Grasscutter
chmod +x gradlew
./gradlew jar # 编译
```

你可以在项目的根目录找到输出的jar。

### 故障排除

获取常见问题的解决方案或寻求帮助，请加入[我们的Discord服务器](https://discord.gg/T5vZU6UyeG)并进入“support”频道。
