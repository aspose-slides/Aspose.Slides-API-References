---
title: aspose.slides.ai
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.ai/
---
包含提供基於 AI 的功能，用於分析和處理 PowerPoint 簡報的類別。

## 類別

| 類別 | 說明 |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient/) | 內建的 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 實作，連接至 Aspose 自家的 LLM。<br/>            這是預設的客戶端，由無參數的 **SlidesAIAgent.#ctor** 建構函式使用。 |
| [`IAIConversation`](/slides/python-net/zh-hant/aspose.slides.ai/iaiconversation/) | 表示一次對話實例。與一般的 AI 呼叫不同，對話會保留完整的上下文。 |
| [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient/) | AI 網路客戶端介面。此介面允許替換不同的 AI 語言模型。<br/>            實作此介面的類別應與 `SlidesAIAgent` 一同使用。 |
| [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient/) | 內建的 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 實作，連接至相容 OpenAI 的 LLM 提供者<br/>            使用指定的基礎 URL。 |
| [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient/) | 內建的 [`IAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/iaiwebclient) 實作，連接至 OpenAI API。 |
| [`SlidesAIAgent`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagent/) | 提供 AI 驅動的功能以處理簡報。 |
| [`SlidesAIAgentException`](/slides/python-net/zh-hant/aspose.slides.ai/slidesaiagentexception/) | 表示與 Slides AI Agent 相關的例外情況。 |

## 列舉

| 列舉類型 | 說明 |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/zh-hant/aspose.slides.ai/presentationcontentamounttype/) | 指定在產生的簡報中包含的內容量，影響投影片的數量以及每張投影片的細節程度。 |