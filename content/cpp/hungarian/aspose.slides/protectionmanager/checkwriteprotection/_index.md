---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API Referenciája
description: Megállapítja, hogy egy prezentáció jelszóval védett-e a módosításhoz.
type: docs
weight: 157
url: /hu/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) metódus

Determines whether a presentation is a password protected to modify.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A jelszó az ellenőrzéshez. |

### Visszatérési érték

True if the password is valid; otherwise, false.
## Megjegyzés

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. A metódus meghívása előtt ellenőrizze a [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) tulajdonságot.
1. Ha a jelszó null vagy üres, ez a metódus false értéket ad vissza.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ProtectionManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)