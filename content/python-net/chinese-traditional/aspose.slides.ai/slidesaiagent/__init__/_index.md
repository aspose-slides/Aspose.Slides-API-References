---
title: SlidesAIAgent constructor
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
使用內建的 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient) 並採用其預設設定，初始化 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent) 的新實例。客戶端連接至 Aspose 自己的 LLM，無需額外設定。若要使用其他 AI 客戶端，請改用 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 之重載。

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
使用自訂 AI 客戶端，初始化 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent) 的新實例。透過此重載可指定 AI 供應商、提供自有 LLM，或自訂連線（例如，提供自訂的 `HttpClient`）。可使用任何 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 的實作，包含：

* [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)

若要使用內建的 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient) 並採用其預設設定，請改用 **SlidesAIAgent.#ctor** 之重載。

```python
def __init__(self, ai_client):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) | AI 客戶端實例。可使用任何 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 的實作。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 未提供 AI 客戶端實例。 |

### 另請參閱
* 類別 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* 類別 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient)
* 類別 [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)
* 類別 [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* 類別 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 程式庫 [`Aspose.Slides`](/slides/python-net)