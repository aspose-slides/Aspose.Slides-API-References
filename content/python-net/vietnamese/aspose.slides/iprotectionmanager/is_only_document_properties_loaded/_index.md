---
title: is_only_document_properties_loaded property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description:
type: docs
url: /vi/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## Thuộc tính is_only_document_properties_loaded
This property makes sense, if presentation file is password protected and document 
            properties of this file are public.
            Value of true means that only document properties are loaded from an encrypted 
            presentation file without use of password.
            Value of false means that entire encrypted presentation is loaded with use of right 
            password, not only document properties are loaded.
            If presentation isn't encrypted then property value is always false.
            If document properties of an encrypted file aren't public then property value is always false.
            If PresentationEx.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded 
            property value is always false.
            Read-only **bool**.

### Định nghĩa:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```


### Xem thêm
* lớp [`IProtectionManager`](/slides/python-net/vi/aspose.slides/iprotectionmanager)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)