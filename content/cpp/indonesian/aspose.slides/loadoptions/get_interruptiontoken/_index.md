---
title: get_InterruptionToken()
second_title: Referensi API Aspose.Slides untuk C++
description: Token untuk memantau permintaan interupsi.
type: docs
weight: 235
url: /id/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() metode


Token untuk memantau permintaan interupsi.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Catatan


Token ini mengelola seluruh siklus hidup instance [IPresentation](../../ipresentation/). Setiap operasi yang berjalan lama, seperti memuat atau menyimpan presentasi, akan diinterupsi dengan memanggil metode [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) milik [InterruptionTokenSource](../../interruptiontokensource/). 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IInterruptionToken](../../iinterruptiontoken/)
* Kelas [LoadOptions](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)