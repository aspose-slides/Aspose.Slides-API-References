---
title: get_IsValid()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika tanda tangan digital ini valid dan dokumen tidak diubah, nilai ini akan menjadi true. Hanya-baca bool.
type: docs
weight: 14
url: /id/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() metode

Jika tanda tangan digital ini valid dan dokumen tidak diubah, nilai ini akan menjadi true. Hanya-baca **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Lihat Juga

* Kelas [IDigitalSignature](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)