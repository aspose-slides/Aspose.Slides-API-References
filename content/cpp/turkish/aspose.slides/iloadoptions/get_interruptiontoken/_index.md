---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API Referansı
description: Kesinti isteklerini izlemek için kullanılan jeton.
type: docs
weight: 235
url: /tr/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() yöntemi

Kesinti isteklerini izlemek için kullanılan jeton.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Açıklamalar

Bu jeton, tüm [IPresentation](../../ipresentation/) örnek ömrünü yönetir. Sunum yükleme veya kaydetme gibi uzun süren herhangi bir işlem, [IInterruptionTokenSource](../../iinterruptiontokensource/) nesnesinin [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) yöntemi çağrılarak kesintiye uğratılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IInterruptionToken](../../iinterruptiontoken/)
* Sınıf [ILoadOptions](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)