---
title: set_Password()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur kata sandi. Tulis System::String."
type: docs
weight: 118
url: /id/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) metode


Mengatur kata sandi. Tulis [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Catatan


Kata sandi. 

Kode contoh berikut menunjukkan cara membuka PowerPoint yang dilindungi kata sandi [Presentation](../../presentation/). 
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