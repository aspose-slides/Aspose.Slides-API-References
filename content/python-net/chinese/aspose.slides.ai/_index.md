---
title: aspose.slides.ai
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/
---
包含提供基于 AI 的功能，用于分析和处理 PowerPoint 演示文稿的类。
## 类

| 类 | 描述 |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient/) | 一个内置的 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 实现，连接到 Aspose 自己的 LLM。<br/>            这是参数无参的 **SlidesAIAgent.#ctor** 构造函数使用的默认客户端。 |
| [`IAIConversation`](/slides/python-net/zh/aspose.slides.ai/iaiconversation/) | 表示一个对话实例。与常规 AI 调用不同，对话会保留完整的上下文。 |
| [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient/) | AI Web 客户端接口。此接口允许替换不同的 AI 语言模型。<br/>            实现此接口的类应与 `SlidesAIAgent` 一起使用。 |
| [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient/) | 一个内置的 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 实现，连接到兼容 OpenAI 的 LLM 提供商<br/>            在指定的基础 URL 上。 |
| [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient/) | 一个内置的 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 实现，连接到 OpenAI API。 |
| [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent/) | 提供用于处理演示文稿的 AI 驱动功能。 |
| [`SlidesAIAgentException`](/slides/python-net/zh/aspose.slides.ai/slidesaiagentexception/) | 表示 Slides AI Agent 相关的异常。 |

## 枚举

| 枚举 | 描述 |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/zh/aspose.slides.ai/presentationcontentamounttype/) | 指定生成的演示文稿中包含的内容量，影响幻灯片的数量以及每张幻灯片的细节程度。 |