---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---


## only_load_document_properties property
This property makes sense, if presentation file is password protected.
            Value of true means that only document properties must be loaded from an encrypted 
            presentation file and password must be ignored.
            Value of false means that entire encrypted presentation must be loaded with use of right 
            password.
            If presentation isn't encrypted then property value is always ignored.
            If document properties of an encrypted file aren't public and property value is true then
            document properties cannot be loaded and exception will be thrown.
            Read-write **bool**.

### Definition:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### See Also
* class [`ILoadOptions`](/slides/python-net/aspose.slides/iloadoptions)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

