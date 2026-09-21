---
title: translate method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
使用 AI（同步版本）將簡報翻譯成指定語言。

```python
def translate(self, presentation, language):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) | 目標簡報 |
| language | **str** | 目標語言 |

### 備註
以下範例使用預設的 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)，它是由無參數的 **SlidesAIAgent.#ctor** 建構函式建立，並連接到 Aspose 自己的 LLM。若要使用不同的 AI 供應者，提供您自己的 LLM，或自訂連線（例如，提供您自己的 `HttpClient`），將 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 實作傳遞給 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 建構函式。可用的實作包括：

* [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 未提供簡報實例 |
| **RuntimeError(Proxy error(ArgumentException))** | 語言值不能為 None 或空值 |

### 另請參閱
* 類別 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* 類別 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)
* 類別 [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* 類別 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 函式庫 [`Aspose.Slides`](/slides/python-net)