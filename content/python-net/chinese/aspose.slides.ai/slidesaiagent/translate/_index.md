---
title: translate method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
使用 AI 将演示文稿翻译为指定语言（同步版本）。

```python
def translate(self, presentation, language):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) | 目标演示文稿 |
| language | **str** | 目标语言 |

### 备注

下面的示例使用默认的 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)，它由无参数的 **SlidesAIAgent.#ctor** 构造函数创建，并连接到 Aspose 自己的 LLM。  
要使用不同的 AI 提供程序，提供您自己的 LLM，或自定义连接（例如，通过提供您自己的 `HttpClient`），将 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 实现传递给 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 构造函数。可用的实现包括：

* [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 未提供演示文稿实例 |
| **RuntimeError(Proxy error(ArgumentException))** | 语言值不能为空或为空 |

### 另请参见
* 类 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* 类 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 类 [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)
* 类 [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* 类 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)