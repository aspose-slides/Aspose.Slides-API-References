---
title: only_load_document_properties property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties properti
Properti ini masuk akal jika file presentasi dilindungi kata sandi.
            Value of true means that only document properties must be loaded from an encrypted 
            presentation file and password must be ignored.
            Value of false means that entire encrypted presentation must be loaded with use of right 
            password.
            If presentation isn't encrypted then property value is always ignored.
            If document properties of an encrypted file aren't public and property value is true then
            document properties cannot be loaded and exception will be thrown.
            Baca/tulis **bool**.

### Definisi:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Lihat Juga
* kelas [`LoadOptions`](/slides/python-net/id/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)