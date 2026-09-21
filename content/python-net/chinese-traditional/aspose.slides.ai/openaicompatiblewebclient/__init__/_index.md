---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
建立一個相容於 OpenAI 的 Web 客戶端實例。


```python
def __init__(self, model, api_key, base_url):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| model | **str** | 由 LLM 供應商支援的模型名稱。 |
| api_key | **str** | API 金鑰（令牌）。 |
| base_url | **str** | OpenAI 相容 LLM 的基礎 URL。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API 金鑰值不能為 None 或空值。 |
| **RuntimeError(Proxy error(ArgumentException))** | 文字模型值不能為 None 或空值。 |
| **RuntimeError(Proxy error(ArgumentException))** | Base URL 值不能為 None 或空值。 |



### 另見
* 類別 [`OpenAICompatibleWebClient`](/slides/python-net/zh-hant/aspose.slides.ai/openaicompatiblewebclient)
* 模組 [`aspose.slides.ai`](/slides/python-net/zh-hant/aspose.slides.ai)
* 函式庫 [`Aspose.Slides`](/slides/python-net)