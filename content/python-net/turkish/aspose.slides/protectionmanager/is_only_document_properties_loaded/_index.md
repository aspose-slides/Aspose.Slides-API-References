---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded özelliği
Bu özellik, sunum dosyası şifre korumalı ve bu dosyanın belge özellikleri genel erişime açıksa anlamlıdır.
True değeri, şifrelenmiş bir sunum dosyasından şifre kullanılmadan yalnızca belge özelliklerinin yüklendiği anlamına gelir.
False değeri, doğru şifre kullanılarak tüm şifrelenmiş sunumun yüklendiği, yalnızca belge özelliklerinin yüklenmediği anlamına gelir.
Sunum şifrelenmemişse özellik değeri her zaman false olur.
Şifrelenmiş bir dosyanın belge özellikleri genel erişime açık değilse özellik değeri her zaman false olur.
Presentation.EncryptDocumentProperties true ise IsOnlyDocumentPropertiesLoaded özelliğinin değeri her zaman false olur.
Salt okunur **bool**.

### Tanım:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`ProtectionManager`](/slides/python-net/tr/aspose.slides/protectionmanager)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)