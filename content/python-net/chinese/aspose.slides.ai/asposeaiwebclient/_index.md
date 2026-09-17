---
title: AsposeAIWebClient class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient 类

一个内置的 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 实现，用于连接 Aspose 自己的 LLM。 这是参数less **SlidesAIAgent.#ctor** 构造函数使用的默认客户端。

AsposeAIWebClient 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient/__init__/#) | 创建一个连接到默认 Aspose LLM 端点的 Aspose AI Web 客户端实例。<br/>            这是参数less **SlidesAIAgent.#ctor** 构造函数使用的客户端，因此只有在将客户端直接传递给 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 构造函数时才需要显式创建。 |
| [`__init__(self, url)`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient/__init__/#str) | 创建一个连接到自定义端点 URL 的 Aspose AI Web 客户端实例。<br/>            当您拥有 Aspose.Slides 团队提供的 URL 时，请使用此重载；否则，请使用带有默认 URL 的 **AsposeAIWebClient.#ctor** 重载。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | 创建一个会话实例。与常规 AI 调用不同，会话会保留完整上下文。 |

### 另请参阅
* 类 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)