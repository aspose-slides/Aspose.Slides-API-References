---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iloadoptions/interruption_token/
weight: 80
---


## interruption_token property
The token to monitor for interruption requests.

This token manages the whole [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as presentaion 
            loading or saving, will be interrupted via calling of the [`IInterruptionTokenSource.interrupt`](/slides/python-net/aspose.slides/iinterruptiontokensource/interrupt) method of 
            the [`IInterruptionTokenSource`](/slides/python-net/aspose.slides/iinterruptiontokensource).

### Definition:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### See Also
* class [`IInterruptionTokenSource`](/slides/python-net/aspose.slides/iinterruptiontokensource)
* class [`ILoadOptions`](/slides/python-net/aspose.slides/iloadoptions)
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

