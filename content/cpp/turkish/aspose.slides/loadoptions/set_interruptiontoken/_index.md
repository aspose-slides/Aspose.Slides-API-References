---
title: set_InterruptionToken()
second_title: Aspose.Slides için C++ API Referansı
description: Kesinti isteklerini izlemek için token.
type: docs
weight: 248
url: /tr/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) yöntem

Kesinti isteklerini izlemek için token.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Açıklamalar

Bu token, bütün [IPresentation](../../ipresentation/) örnek ömrünü yönetir. Sunumu yükleme veya kaydetme gibi uzun süreli işlemler, [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) yöntemi [InterruptionTokenSource](../../interruptiontokensource/)'nin çağrılmasıyla kesintiye uğratılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IInterruptionToken](../../iinterruptiontoken/)
* Sınıf [LoadOptions](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)