---
title: get_InterruptionToken()
second_title: Referensi API Aspose.Slides untuk C++
description: Token untuk memantau permintaan interupsi.
type: docs
weight: 235
url: /id/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() metode


Token untuk memantau permintaan interupsi.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Keterangan


Token ini mengelola seluruh masa hidup instance [IPresentation](../../ipresentation/). Setiap operasi yang berjalan lama, seperti pemuatan atau penyimpanan presentasi, akan diinterupsi dengan memanggil metode [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) dari [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IInterruptionToken](../../iinterruptiontoken/)
* Kelas [ILoadOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)