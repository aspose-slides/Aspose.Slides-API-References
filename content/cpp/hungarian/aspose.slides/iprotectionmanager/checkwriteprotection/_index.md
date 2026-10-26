---
title: CheckWriteProtection()
second_title: Aspose.Slides C++ API Referenciája
description: Megállapítja, hogy egy prezentáció jelszóval védett-e a módosításhoz.
type: docs
weight: 157
url: /hu/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) metódus


Megállapítja, hogy a prezentáció módosítása jelszóval védett-e.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A jelszó az ellenőrzéshez. |

### Visszatérési érték

Igaz, ha a jelszó érvényes; egyébként hamis.

## Megjegyzés



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. A metódus meghívása előtt ellenőriznie kell a [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) tulajdonságot.
1. Ha a jelszó null vagy üres, ez a metódus hamisat ad vissza.


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IProtectionManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)