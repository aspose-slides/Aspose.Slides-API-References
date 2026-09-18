---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded özellik
Bu özellik, sunum dosyası şifre korumalı ve bu dosyanın belge özellikleri genel ise anlamlıdır.
            true değerinin anlamı, şifreli bir sunum dosyasından şifre kullanılmadan yalnızca belge özelliklerinin yüklenmesidir.
            false değerinin anlamı, doğru şifre kullanılarak tüm şifreli sunumun yüklendiği ve yalnızca belge özelliklerinin yüklenmediğidir.
            Sunum şifrelenmemişse, özellik değeri her zaman false olur.
            Şifreli bir dosyanın belge özellikleri genel değilse, özellik değeri her zaman false olur.
            Eğer PresentationEx.EncryptDocumentProperties true ise, IsOnlyDocumentPropertiesLoaded özellik değeri her zaman false olur.
            Salt okunur **bool**.

### Tanım:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Ayrıca Bakınız
* sınıf [`IProtectionManager`](/slides/python-net/tr/aspose.slides/iprotectionmanager)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)