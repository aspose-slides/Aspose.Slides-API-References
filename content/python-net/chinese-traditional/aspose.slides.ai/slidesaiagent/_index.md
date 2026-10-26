---
title: SlidesAIAgent class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent 類別

提供用於處理簡報的 AI 功能。

SlidesAIAgent 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | 使用自訂 AI 用戶端初始化 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent) 的新執行個體。<br/>            使用此多載以指定 AI 提供者、提供自己的 LLM，或自訂<br/>            連線（例如，提供自己的 `HttpClient`）。<br/>            可以使用任何 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 的實作，包括：<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            如欲使用內建的 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient) 及其預設配置，<br/>            請改用 **SlidesAIAgent.#ctor** 多載。 |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent/__init__/#) | 使用內建的 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)（預設配置）初始化 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent) 的新執行個體。<br/>            客戶端連接至 Aspose 自有的 LLM，且不需要額外配置。<br/>            如欲使用不同的 AI 用戶端，請改用 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 多載。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | 從文字描述產生簡報執行個體。提供所需語言的主題、想法、引句或文字片段。 |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | 從文字描述產生簡報執行個體。提供所需語言的主題、想法、引句或文字片段。 |
| [`translate(self, presentation, language)`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | 使用 AI（同步版本）將簡報翻譯為指定語言。 |

### 另請參閱
* 類別 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* 類別 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient)
* 類別 [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)
* 類別 [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* 類別 [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 函式庫 [`Aspose.Slides`](/slides/python-net)