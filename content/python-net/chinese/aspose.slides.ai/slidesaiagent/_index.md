---
title: SlidesAIAgent class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent 类

提供用于处理演示文稿的 AI 驱动功能。

SlidesAIAgent 类型公开以下成员：

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | 使用自定义 AI 客户端初始化 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent) 的新实例。<br/>            使用此重载可以指定 AI 提供程序，提供您自己的 LLM，或自定义<br/>            连接（例如，通过提供您自己的 `HttpClient`）。<br/>            可以使用任何 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 的实现，包括：<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            要使用内置的 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient) 并使用其默认配置，<br/>            请改用 **SlidesAIAgent.#ctor** 重载。 |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent/__init__/#) | 使用内置的<br/>            [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)（默认配置）初始化 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent) 的新实例。客户端连接到<br/>            Aspose 自己的 LLM，无需额外配置。<br/>            要使用其他 AI 客户端，请改用 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 重载。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | 根据文本描述生成演示文稿实例。提供所需语言的主题、想法、引用或文本片段。 |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | 根据文本描述生成演示文稿实例。提供所需语言的主题、想法、引用或文本片段。 |
| [`translate(self, presentation, language)`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | 使用 AI 将演示文稿翻译为指定语言（同步版本）。 |

### 另请参见
* 类 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* 类 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient)
* 类 [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)
* 类 [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* 类 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)