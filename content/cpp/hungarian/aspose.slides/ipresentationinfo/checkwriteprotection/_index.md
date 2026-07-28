---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API Referencia
description: Ellenőrzi, hogy a módosításhoz szükséges jelszó helyes-e egy írásvédett prezentáció esetén.
type: docs
weight: 66
url: /hu/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) metódus

Ellenőrzi, hogy a módosításhoz szükséges jelszó helyes-e egy írásvédett bemutató esetén.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Az ellenőrzendő jelszó. |

### Visszatérési érték

Igaz, ha a bemutató írásvédett és a jelszó helyes. Hamis egyébként.

## Megjegyzések

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. A metódus meghívása előtt ellenőriznie kell a [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) tulajdonságot.
1. Ha a jelszó null vagy üres, ez a metódus hamisat ad vissza.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IPresentationInfo](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)