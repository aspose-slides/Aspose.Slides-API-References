---
title: get_IsPasswordProtected()
second_title: Aspose.Slides untuk Referensi API C++
description: Menunjukkan apakah VBAProject dilindungi oleh password untuk melihat properti proyek. Baca-saja bool.
type: docs
weight: 40
url: /id/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() metode


Menunjukkan apakah VBAProject dilindungi oleh password untuk melihat properti proyek. Baca-saja **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Catatan



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Lihat Juga

* Kelas [VbaProject](../)
* Ruang Nama [Aspose::Slides::Vba](../../)
* Perpustakaan [Aspose.Slides](../../../)