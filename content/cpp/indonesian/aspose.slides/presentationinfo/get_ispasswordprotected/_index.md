---
title: get_IsPasswordProtected()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi oleh kata sandi untuk dibuka.
type: docs
weight: 14
url: /id/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() metode


Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi oleh kata sandi untuk dibuka.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Catatan



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Lihat Juga

* Kelas [PresentationInfo](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)