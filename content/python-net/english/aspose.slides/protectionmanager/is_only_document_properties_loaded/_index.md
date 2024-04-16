---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---


## is_only_document_properties_loaded property
This property makes sense, if presentation file is password protected and document 
            properties of this file are public.
            Value of true means that only document properties are loaded from an encrypted 
            presentation file without use of password.
            Value of false means that entire encrypted presentation is loaded with use of right 
            password, not only document properties are loaded.
            If presentation isn't encrypted then property value is always false.
            If document properties of an encrypted file aren't public then property value is always false.
            If Presentation.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded 
            property value is always false.
            Read-only **bool**.

### Definition:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```


### See Also
* class [`ProtectionManager`](/slides/python-net/aspose.slides/protectionmanager)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

