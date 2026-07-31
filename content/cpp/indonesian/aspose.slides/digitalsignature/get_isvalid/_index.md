---
title: get_IsValid()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika tanda tangan digital ini valid dan dokumen tidak telah diubah, nilai ini akan menjadi true. Baca-saja bool.
type: docs
weight: 14
url: /id/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() metode


Jika tanda tangan digital ini valid dan dokumen tidak telah diubah, nilai ini akan menjadi true. Baca-saja **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
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

* Kelas [DigitalSignature](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)