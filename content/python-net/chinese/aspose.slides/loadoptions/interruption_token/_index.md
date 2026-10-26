---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token 属性
用于监视中断请求的令牌.

此令牌管理整个 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例的生命周期。任何长期运行的操作，例如加载或保存演示文稿，都将通过调用 [`InterruptionTokenSource`](/slides/python-net/zh/aspose.slides/interruptiontokensource) 的 [`InterruptionTokenSource.interrupt`](/slides/python-net/zh/aspose.slides/interruptiontokensource/interrupt) 方法来中断。

### 定义:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### 另请参阅
* 类 [`InterruptionTokenSource`](/slides/python-net/zh/aspose.slides/interruptiontokensource)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 类 [`LoadOptions`](/slides/python-net/zh/aspose.slides/loadoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)