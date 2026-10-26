---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties özelliği
Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır.
            true değerinin anlamı, yalnızca belge özelliklerinin şifrelenmiş 
            sunum dosyasından yüklenmesi gerektiği ve şifrenin göz ardı edilmesi gerektiğidir.
            false değerinin anlamı, doğru şifre kullanılarak tüm şifreli sunumun 
            yüklenmesi gerektiğidir.
            Sunum şifrelenmemişse özellik değeri her zaman göz ardı edilir.
            Şifreli bir dosyanın belge özellikleri herkese açık değilse ve özellik değeri true ise
            belge özellikleri yüklenemez ve bir istisna fırlatılır.
            Okuma/Yazma **bool**.

### Tanım:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Ayrıca Bakınız
* sınıf [`LoadOptions`](/slides/python-net/tr/aspose.slides/loadoptions)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)