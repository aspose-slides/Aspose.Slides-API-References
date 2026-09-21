---
title: OpenAIWebClient constructor
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
建立 OpenAI 網路客戶端的實例。


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| model | **str** | OpenAI 語言模型。可能的值：<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API 金鑰。 |
| organization_id | **str** | 組織 ID（可選）。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API 金鑰的值不能為 None 或空值。 |
| **RuntimeError(Proxy error(ArgumentException))** | 文字模型的值不能為 None 或空值。 |



### 另請參閱
* 類別 [`OpenAIWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaiwebclient)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 函式庫 [`Aspose.Slides`](/slides/python-net)