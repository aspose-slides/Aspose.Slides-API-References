---
title: get_IsWriteProtected()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan nilai yang menunjukkan apakah presentasi yang terikat dilindungi penulisan.
type: docs
weight: 27
url: /id/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() metode

Mendapatkan nilai yang menunjukkan apakah presentasi yang terikat dilindungi penulisan.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Keterangan

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

Jika presentasi dilindungi oleh kata sandi untuk dibuka, nilai properti sama dengan NotDefined.

## Lihat Juga

* Enum [NullableBool](../../nullablebool/)
* Kelas [PresentationInfo](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)