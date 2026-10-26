---
title: SlidesAIAgent constructor
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
使用内置的 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient) 并采用默认配置来初始化 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent) 的新实例。客户端连接到 Aspose 的 LLM，无需额外配置。若要使用其他 AI 客户端，请改为使用 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 重载。

```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
使用自定义 AI 客户端初始化 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent) 的新实例。使用此重载可以指定 AI 提供商、提供您自己的 LLM，或自定义连接（例如，提供您自己的 `HttpClient`）。可以使用任何 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 的实现，包括：

* [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)

若要使用内置的 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)（默认配置），请改为使用 **SlidesAIAgent.#ctor** 重载。

```python
def __init__(self, ai_client):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) | AI 客户端实例。可以使用任何 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient) 的实现。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 未提供 AI 客户端实例。 |

### 另见
* 类 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* 类 [`IAIWebClient`](/slides/python-net/zh/aspose.slides.ai/iaiwebclient)
* 类 [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)
* 类 [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* 类 [`SlidesAIAgent`](/slides/python-net/zh/aspose.slides.ai/slidesaiagent)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)