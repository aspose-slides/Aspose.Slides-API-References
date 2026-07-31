---
title: get_SignTime()
second_title: Referensi API Aspose.Slides untuk C++
description: "Waktu ketika dokumen ditandatangani. Hanya-baca System::DateTime."
type: docs
weight: 27
url: /id/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() metode


Waktu ketika dokumen ditandatangani. Hanya-baca [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Keterangan



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Lihat Juga

* Kelas [DateTime](../../../system/datetime/)
* Kelas [IDigitalSignature](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)