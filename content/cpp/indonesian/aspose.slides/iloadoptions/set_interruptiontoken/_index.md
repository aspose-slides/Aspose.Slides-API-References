---
title: set_InterruptionToken()
second_title: Referensi API Aspose.Slides untuk C++
description: Token untuk memantau permintaan interupsi.
type: docs
weight: 248
url: /id/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metode


Token untuk memantau permintaan interupsi.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Catatan


Token ini mengelola masa hidup seluruh instance [IPresentation](../../ipresentation/). Setiap operasi yang memakan waktu lama, seperti pemuatan atau penyimpanan presentasi, akan terinterupsi dengan memanggil metode [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) dari [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IInterruptionToken](../../iinterruptiontoken/)
* Kelas [ILoadOptions](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)