

> 本文示例配置文件已上传至我的`Github`仓库[https://github.com/CNFeffery/DataScienceStudyNotes](https://github.com)


# 1 简介


　　大家好我是费老师，最近国产大模型`Deepseek v3`新版本凭借其优秀的模型推理能力，讨论度非常之高🔥，且其官网提供的相关大模型API接口服务价格一直走的“价格屠夫”路线，性价比很高，本期文章中，就将为大家举例，如何在`vscode`中，基于开源AI编程辅助插件`Continue`，配置基于`Deepseek`的API接口，实现常用的AI编程辅助等功能。


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155829340-2040987696.png)](https://github.com)
# 2 Continue\+Deepseek实现AI编程辅助


## 2\.1 安装Continue


　　`Continue`是一款非常流行的开源AI编程辅助工具（仓库地址：[https://github.com/continuedev/continue](https://github.com) ），可在`vscode`、`pycharm`等多种常见ide中安装使用，我们直接在`vscode`插件市场中搜索安装即可：


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155832321-1069900471.png)](https://github.com)
## 2\.2 创建Deepseek API密钥


　　接下来我们来到`Deepseek`这边，创建供`Continue`使用的API密钥。


　　访问`Deepseek`开放平台对应页面（ [https://platform.deepseek.com/api\_keys](https://github.com) ），点击**创建API key**：


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155834436-168810106.png)](https://github.com)
　　按引导完成新的密钥创建，记得复制之后**妥善保存**该密钥：


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155836648-895840018.png)](https://github.com)
## 2\.3 修改Continue配置


　　接下来我们直接对`Continue`的配置进行更新。


　　`vscode`中点击侧边栏中的`Continue`图标后，点击面板右上方的*设置图标*打开配置文件进行编辑，参考下图中格式添加相关`deepseek-coder`模型，其中`apiKey`填入前面创建的**API密钥**：


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155838645-1331564678.png)](https://github.com):[蓝猫机场](https://fenfang.org)
　　完整的配置参数参考，请移步文章开头`Github`仓库。


## 2\.4 使用相关AI编程辅助功能


　　按照上文过程完成相关配置后，我们来测试一下`Continue`中常用的一些功能是否生效：


### 2\.4\.1 对话功能


　　在点击`vscode`侧边栏`Continue`图标后展开的面板中，我们可以直接进行最基础的AI对话问答，注意切换到前面配置的对应模型：


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155840803-690599153.png)](https://github.com)
[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155842603-1653433886.png)](https://github.com)
　　可以看到，`Deepseek`接口应用成功🎉\~


### 2\.4\.2 代码智能补全功能


　　常用的代码智能补全功能，生成速度很快：


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155844510-2033348307.gif)](https://github.com)
### 2\.4\.3 代码智能生成功能


　　在空的文件中按下快捷键`Ctrl+I`，可以根据需求描述直接生成完整代码：


[![](https://img2024.cnblogs.com/blog/1344061/202412/1344061-20241230155846478-1775033457.gif)](https://github.com)
　　更多内容，请移步相关文档学习更多：


* `Continue`官网：[https://www.continue.dev](https://github.com)
* `Deepseek`文档：[https://platform.deepseek.com/usage](https://github.com)




---


　　以上就是本文的全部内容，欢迎在评论区与我们进行讨论\~


