---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API Referansı
description: Kesinti isteklerini izlemek için kullanılan token.
type: docs
weight: 235
url: /tr/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() metodu


Bu token, kesinti isteklerini izlemek için kullanılır.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Açıklamalar


Bu token, tüm [IPresentation](../../ipresentation/) örnek ömrünü yönetir. Sunumu yükleme veya kaydetme gibi uzun süren işlemler, [InterruptionTokenSource](../../interruptiontokensource/)'ın [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) metodu çağrılarak kesintiye uğratılacaktır. 

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IInterruptionToken](../../iinterruptiontoken/)
* Sınıf [LoadOptions](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)