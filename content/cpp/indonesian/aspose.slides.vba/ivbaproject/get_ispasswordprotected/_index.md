---
title: get_IsPasswordProtected()
second_title: Aspose.Slides untuk Referensi API C++
description: Menunjukkan apakah VBAProject dilindungi oleh kata sandi untuk melihat properti proyek. Hanya-baca bool.
type: docs
weight: 40
url: /id/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() metode


Menunjukkan apakah VBAProject dilindungi oleh kata sandi untuk melihat properti proyek. Hanya-baca **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Kelas [IVbaProject](../)
* Ruang Nama [Aspose::Slides::Vba](../../)
* Perpustakaan [Aspose.Slides](../../../)