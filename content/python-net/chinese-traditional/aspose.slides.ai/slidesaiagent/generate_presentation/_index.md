---
title: generate_presentation method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
根據文字說明產生簡報實例。提供主題、想法、引文或文字片段，使用所需的語言。

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| description | **str** | 主題、想法、引文或文字片段。 |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/zh-hant/aspose.slides.ai/presentationcontentamounttype) | 產生簡報的內容數量。 |

### 備註

以下範例使用預設的 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)，它由無參數 **SlidesAIAgent.#ctor** 建構函式建立，並連接至 Aspose 自家的 LLM。若要使用其他 AI 供應商，提供您自己的 LLM，或自訂連線（例如，提供您自己的 `HttpClient`），將 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 實作傳遞給 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 建構函式。可用的實作包括：

* [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)

### 例外情況

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | AI 聊天指令不能為 None 或空值。 |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
根據文字說明產生簡報實例。提供主題、想法、引文或文字片段，使用所需的語言。

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| description | **str** | 主題、想法、引文或文字片段。 |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/zh-hant/aspose.slides.ai/presentationcontentamounttype) | 產生簡報的內容數量。 |
| presentation_template | [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) | 用於版面配置與設計的簡報範本，取代預設範本。 |

### 備註

以下範例使用預設的 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)，它由無參數 **SlidesAIAgent.#ctor** 建構函式建立，並連接至 Aspose 自家的 LLM。若要使用其他 AI 供應商，提供您自己的 LLM，或自訂連線（例如，提供您自己的 `HttpClient`），將 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 實作傳遞給 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 建構函式。可用的實作包括：

* [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)

### 例外情況

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 未提供簡報範本。 |
| **RuntimeError(Proxy error(ArgumentException))** | AI 聊天指令不能為 None 或空值。 |

### 另請參閱
* 類別 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* 類別 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 類別 [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)
* 類別 [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* 列舉 [`PresentationContentAmountType`](/slides/python-net/zh-hant/aspose.slides.ai/presentationcontentamounttype)
* 類別 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 函式庫 [`Aspose.Slides`](/slides/python-net)