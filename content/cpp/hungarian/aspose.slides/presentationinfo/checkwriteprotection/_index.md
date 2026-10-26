---
title: CheckWriteProtection()
second_title: Aspose.Slides C++ API referenciája
description: Ellenőrzi, hogy a módosításhoz szükséges jelszó helyes-e egy írásvédett bemutató esetén.
type: docs
weight: 66
url: /hu/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) method

Ellenőrzi, hogy a módosításhoz szükséges jelszó helyes-e egy írásvédett bemutató esetén.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A ellenőrzendő jelszó. |

### Visszatérési érték

True, ha a bemutató írásvédett és a jelszó helyes. Egyébként False.

## Megjegyzések

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Ellenőriznie kell a [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) tulajdonságot, mielőtt meghívja ezt a metódust.
1. Ha a jelszó null vagy üres, ez a metódus false értéket ad vissza.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [PresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)