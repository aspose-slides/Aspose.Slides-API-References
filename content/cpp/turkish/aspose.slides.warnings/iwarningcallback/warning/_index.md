---
title: Warning()
second_title: Aspose.Slides for C++ API Referansı
description: Uyarıyı alan ve işlemin iptal edilip edilmemesi gerektiğine karar veren geri arama metodu.
type: docs
weight: 1
url: /tr/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) metodu


Uyarıyı alan ve işlemin iptal edilip edilmemesi gerektiğine karar veren geri arama metodu.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | İşlenecek uyarı. |

### Dönüş Değeri

İptal kararı [ReturnAction](../../returnaction/).

## Ayrıca Bakınız

* Numaralandırma [ReturnAction](../../returnaction/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IWarningInfo](../../iwarninginfo/)
* Sınıf [IWarningCallback](../)
* İsim Alanı [Aspose::Slides::Warnings](../../)
* Kütüphane [Aspose.Slides](../../../)