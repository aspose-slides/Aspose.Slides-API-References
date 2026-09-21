---
title: AsposeAIWebClient class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient 類別

內建的 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 實作，可連接至 Aspose 自己的 LLM。這是參數為空的 **SlidesAIAgent.#ctor** 建構函式使用的預設用戶端。

AsposeAIWebClient 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient/__init__/#) | 建立一個連接至預設 Aspose LLM 端點的 Aspose AI 網路用戶端實例。<br/>            這是參數為空的 **SlidesAIAgent.#ctor** 建構函式使用的用戶端，因此只有在將用戶端直接傳遞給 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 建構函式時才需要明確建立。 |
| [`__init__(self, url)`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient/__init__/#str) | 建立一個連接至自訂端點 URL 的 Aspose AI 網路用戶端實例。當你擁有 Aspose.Slides 團隊提供的 URL 時，使用此<br/>            多載；否則，使用帶有預設 URL 的 **AsposeAIWebClient.#ctor** 多載。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | 建立會話實例。與一般的 AI 呼叫不同，會話會保留完整的上下文。 |

### 另請參閱
* 類別 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 函式庫 [`Aspose.Slides`](/slides/python-net)