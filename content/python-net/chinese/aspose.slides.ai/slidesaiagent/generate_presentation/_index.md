---
title: generate_presentation method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
根据文本描述生成演示文稿实例。提供所需语言的主题、想法、引语或文本片段。


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| description | **str** | 主题、想法、引语或文本片段。 |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/zh/aspose.slides.ai/presentationcontentamounttype) | 生成的演示文稿中的内容数量。 |

### 备注

下面的示例使用默认的 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)，该实例由无参 **SlidesAIAgent.#ctor** 构造函数创建，并连接到 Aspose 自己的 LLM。要使用其他 AI 提供商，提供您自己的 LLM，或自定义连接（例如，提供您自己的 `HttpClient`），将 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 实现传递给 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 构造函数。可用的实现包括：
             
* [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI 聊天指令不能为 None 或为空。 |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
根据文本描述生成演示文稿实例。提供所需语言的主题、想法、引语或文本片段。


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| description | **str** | 主题、想法、引语或文本片段。 |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/zh/aspose.slides.ai/presentationcontentamounttype) | 生成的演示文稿中的内容数量。 |
| presentation_template | [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) | 用作布局和设计模板的演示文稿，替代默认模板。 |

### 备注

下面的示例使用默认的 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)，该实例由无参 **SlidesAIAgent.#ctor** 构造函数创建，并连接到 Aspose 自己的 LLM。要使用其他 AI 提供商，提供您自己的 LLM，或自定义连接（例如，提供您自己的 `HttpClient`），将 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 实现传递给 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 构造函数。可用的实现包括：
            
* [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 未提供演示文稿模板。 |
| **RuntimeError(Proxy error(ArgumentException))** | AI 聊天指令不能为 None 或为空。 |



### 另请参阅
* 类 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* 类 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 类 [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)
* 类 [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* 枚举 [`PresentationContentAmountType`](/slides/python-net/zh/aspose.slides.ai/presentationcontentamounttype)
* 类 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)