---
title: get_Password()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mendapatkan kata sandi. Baca System::String."
type: docs
weight: 105
url: /id/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() metode

Mendapatkan kata sandi. Baca [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Catatan

Kata sandi. 

Contoh kode berikut menunjukkan cara membuka PowerPoint yang dilindungi kata sandi [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// bekerja dengan presentasi yang didekripsi
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [LoadOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)