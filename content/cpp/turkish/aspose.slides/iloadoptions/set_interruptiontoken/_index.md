---
title: set_InterruptionToken()
second_title: Aspose.Slides için C++ API Referansı
description: Kesinti isteklerini izlemek için kullanılan belirteç.
type: docs
weight: 248
url: /tr/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metot


Kesinti isteklerini izlemek için kullanılan belirteç.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Açıklamalar


Bu belirteç, tüm [IPresentation](../../ipresentation/) örnek ömrünü yönetir. Sunum yükleme veya kaydetme gibi uzun süren herhangi bir işlem, [IInterruptionTokenSource](../../iinterruptiontokensource/)'nin [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) yöntemi çağrılarak kesintiye uğratılacaktır. 
## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IInterruptionToken](../../iinterruptiontoken/)
* Sınıf [ILoadOptions](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)