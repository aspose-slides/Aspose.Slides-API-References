---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties özelliği
Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır.
            Doğru değeri, yalnızca belge özelliklerinin şifreli bir 
            sunum dosyasından yüklenmesi gerektiği ve şifrenin yok sayılması gerektiği anlamına gelir.
            Yanlış değeri, tüm şifreli sunumun doğru 
            şifre kullanılarak yüklenmesi gerektiği anlamına gelir.
            Sunum şifrelenmemişse, özellik değeri her zaman yok sayılır.
            Şifreli bir dosyanın belge özellikleri kamuya açık değilse ve özellik değeri doğru ise
            belge özellikleri yüklenemez ve bir istisna fırlatılır.
            Okunabilir-yazılabilir **bool**.

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
* sınıf [`ILoadOptions`](/slides/python-net/tr/aspose.slides/iloadoptions)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)