---
title: get_IsWriteProtected()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nilai yang menunjukkan apakah presentasi yang terikat dilindungi penulisan.
type: docs
weight: 27
url: /id/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() metode


Mendapatkan nilai yang menunjukkan apakah presentasi yang terikat dilindungi penulisan.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Catatan



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Jika presentasi dilindungi dengan kata sandi untuk membuka, nilai properti sama dengan NotDefined. Lihat [NullableBool](../../nullablebool/) enumerasi.
## Lihat Juga

* Enum [NullableBool](../../nullablebool/)
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)