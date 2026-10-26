---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
OpenAI 互換 Web クライアントのインスタンスを作成します。

```python
def __init__(self, model, api_key, base_url):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| model | **str** | LLM プロバイダーがサポートするモデル名。 |
| api_key | **str** | API キー（トークン）。 |
| base_url | **str** | OpenAI 互換 LLM のベース URL。 |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API キーの値は None または空にできません。 |
| **RuntimeError(Proxy error(ArgumentException))** | テキストモデルの値は None または空にできません。 |
| **RuntimeError(Proxy error(ArgumentException))** | ベース URL の値は None または空にできません。 |

### See Also
* class [`OpenAICompatibleWebClient`](/slides/python-net/ja/aspose.slides.ai/openaicompatiblewebclient)
* module [`aspose.slides.ai`](/slides/python-net/ja/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)