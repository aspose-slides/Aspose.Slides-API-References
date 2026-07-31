---
title: get_SignTime()
second_title: Referensi API Aspose.Slides untuk C++
description: "Waktu saat dokumen ditandatangani. Hanya baca System::DateTime."
type: docs
weight: 27
url: /id/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() metode


Waktu saat dokumen ditandatangani. Hanya baca [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## Lihat Juga

* Kelas [DateTime](../../../system/datetime/)
* Kelas [DigitalSignature](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)