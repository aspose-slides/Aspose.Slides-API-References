---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token 属性
用于监视中断请求的令牌。

此令牌管理整个 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例的生命周期。任何长时间运行的操作，例如呈现加载或保存，都将通过调用 [`IInterruptionTokenSource`](/slides/python-net/zh/aspose.slides/iinterruptiontokensource) 的 [`IInterruptionTokenSource.interrupt`](/slides/python-net/zh/aspose.slides/iinterruptiontokensource/interrupt) 方法来中断。

### 定义：
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### 另见
* 类 [`IInterruptionTokenSource`](/slides/python-net/zh/aspose.slides/iinterruptiontokensource)
* 类 [`ILoadOptions`](/slides/python-net/zh/aspose.slides/iloadoptions)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)