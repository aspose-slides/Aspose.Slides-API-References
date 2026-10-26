---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
创建一个连接到默认 Aspose LLM 端点的 Aspose AI web client 实例。
这是参数无的 **SlidesAIAgent.#ctor** 构造函数使用的客户端，因此只有在直接将该客户端传递给 **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** 构造函数时才需要显式创建它。


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
创建一个连接到自定义端点 URL 的 Aspose AI web client 实例。当您拥有由 Aspose.Slides 团队提供的 URL 时使用此重载；否则，请使用带有默认 URL 的 **AsposeAIWebClient.#ctor** 重载。


```python
def __init__(self, url):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| url | **str** | Aspose LLM 的端点 URL，由 Aspose.Slides 团队提供。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL 不能为空或为空字符串。 |



### 另见
* 类 [`AsposeAIWebClient`](/slides/python-net/zh/aspose.slides.ai/asposeaiwebclient)
* 模块 [`aspose.slides.ai`](/slides/python-net/zh/aspose.slides.ai)
* 库 [`Aspose.Slides`](/slides/python-net)