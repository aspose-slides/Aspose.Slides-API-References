---
title: OpenAIWebClient constructor
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
创建 OpenAI Web 客户端的实例。

```python
def __init__(self, model, api_key, organization_id):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| model | **str** | OpenAI 语言模型。可能的取值：<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API 密钥。 |
| organization_id | **str** | 组织 ID（可选）。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API key 值不能为 None 或为空。 |
| **RuntimeError(Proxy error(ArgumentException))** | 文本模型值不能为 None 或为空。 |

### 另见
* 类 [`OpenAIWebClient`](/slides/python-net/zh/aspose.slides.ai/openaiwebclient)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)