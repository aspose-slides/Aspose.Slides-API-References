---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
建立一個連接到預設 Aspose LLM 端點的 Aspose AI 網路客戶端實例。  
此客戶端是參數為空的 **SlidesAIAgent.#ctor** 建構函式所使用的，所以僅在將客戶端傳遞給 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 建構函式時才需要明確建立它。

```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
建立一個連接到自訂端點 URL 的 Aspose AI 網路客戶端實例。  
當您擁有由 Aspose.Slides 團隊提供的 URL 時，請使用此重載；否則，請使用帶有預設 URL 的 **AsposeAIWebClient.#ctor** 重載。

```python
def __init__(self, url):
    ...
```


| 參數 | 類型 | 描述 |
| :- | :- | :- |
| url | **str** | Aspose LLM 的端點 URL，由 Aspose.Slides 團隊提供。 |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL 不能為 None 或空值。 |



### 另請參閱
* 類別 [`AsposeAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/asposeaiwebclient)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 函式庫 [`Aspose.Slides`](/slides/python-net)