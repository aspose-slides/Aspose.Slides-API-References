---
title: get_IsPasswordProtected()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil nilai yang menunjukkan apakah presentasi yang terikat dilindungi oleh kata sandi untuk dibuka.
type: docs
weight: 14
url: /id/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() metode

Mendapatkan nilai yang menunjukkan apakah presentasi yang terikat dilindungi oleh kata sandi untuk dibuka.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Catatan



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Lihat Juga

* Kelas [IPresentationInfo](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)