---
title: set_InterruptionToken()
second_title: Referensi API Aspose.Slides untuk C++
description: Token yang digunakan untuk memantau permintaan penghentian.
type: docs
weight: 248
url: /id/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metode

Token yang digunakan untuk memantau permintaan penghentian.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Catatan

Token ini mengelola seluruh masa hidup instance [IPresentation](../../ipresentation/). Setiap operasi yang memakan waktu lama, seperti memuat atau menyimpan presentasi, akan dihentikan dengan memanggil metode [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) dari [InterruptionTokenSource](../../interruptiontokensource/). 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IInterruptionToken](../../iinterruptiontoken/)
* Kelas [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)