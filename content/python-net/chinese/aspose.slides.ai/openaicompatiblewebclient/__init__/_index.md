---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
创建一个兼容 OpenAI 的 Web 客户端实例。


```python
def __init__(self, model, api_key, base_url):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| model | **str** | 受 LLM 提供者支持的模型名称。 |
| api_key | **str** | API 密钥（令牌）。 |
| base_url | **str** | OpenAI 兼容的 LLM 的基础 URL。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API 密钥的值不能为空或为空。 |
| **RuntimeError(Proxy error(ArgumentException))** | 文本模型的值不能为空或为空。 |
| **RuntimeError(Proxy error(ArgumentException))** | Base URL 的值不能为空或为空。 |



### 另请参阅
* 类 [`OpenAICompatibleWebClient`](/slides/python-net/zh/aspose.slides.ai/openaicompatiblewebclient)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)