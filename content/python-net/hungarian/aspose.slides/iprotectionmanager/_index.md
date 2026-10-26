---
title: IProtectionManager class
second_title: Aspose.Slides a Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/iprotectionmanager/
---
## IProtectionManager osztály

Prezentáció jelszóvédelmének kezelése.

Az IProtectionManager típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/hu/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Ez a tulajdonság akkor értelmes, ha a prezentáció jelszóval védett.<br/>            Ha true akkor a dokumentumtulajdonságok titkosítva vannak a prezentáció fájlban.<br/>            Ha false akkor a dokumentumtulajdonságok nyilvánosak, míg a prezentáció titkosított.<br/>            Olvasás/írás **bool**. |
| [`is_encrypted`](/slides/python-net/hu/aspose.slides/iprotectionmanager/is_encrypted/) | Megadja, hogy ez a példány titkosított-e.<br/>            Csak-olvasás **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/hu/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Ez a tulajdonság akkor értelmes, ha a prezentáció fájl jelszóval védett és a dokumentumtulajdonságok nyilvánosak.<br/>            A true érték azt jelenti, hogy csak a dokumentumtulajdonságok töltődnek be egy titkosított prezentációból jelszó használata nélkül.<br/>            A false érték azt jelenti, hogy az egész titkosított prezentáció betöltődik a megfelelő jelszóval, nem csak a dokumentumtulajdonságok.<br/>            Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig false.<br/>            Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, akkor a tulajdonság értéke mindig false.<br/>            Ha a PresentationEx.EncryptDocumentProperties true, akkor az IsOnlyDocumentPropertiesLoaded tulajdonság értéke mindig false.<br/>            Csak-olvasás **bool**. |
| [`is_write_protected`](/slides/python-net/hu/aspose.slides/iprotectionmanager/is_write_protected/) | Megadja, hogy ez a prezentáció írásvédett-e.<br/>            Csak-olvasás **bool**. |
| [`encryption_password`](/slides/python-net/hu/aspose.slides/iprotectionmanager/encryption_password/) | Visszaadja a titkosítási jelszót.<br/>            Csak-olvasás **str**. |
| [`read_only_recommended`](/slides/python-net/hu/aspose.slides/iprotectionmanager/read_only_recommended/) | Olvasás-csak ajánlás beállítása vagy lekérése.<br/>            Olvasás/írás **bool**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/hu/aspose.slides/iprotectionmanager/encrypt/#str) | Titkosítja a prezentációt a megadott jelszóval. |
| [`remove_encryption(self)`](/slides/python-net/hu/aspose.slides/iprotectionmanager/remove_encryption/#) | Eltávolítja a titkosítást. |
| [`set_write_protection(self, password)`](/slides/python-net/hu/aspose.slides/iprotectionmanager/set_write_protection/#str) | Írásvédelmet állít be ehhez a prezentációhoz a megadott jelszóval. |
| [`remove_write_protection(self)`](/slides/python-net/hu/aspose.slides/iprotectionmanager/remove_write_protection/#) | Eltávolítja az írásvédelmet ehhez a prezentációhoz. |
| [`check_write_protection(self, password)`](/slides/python-net/hu/aspose.slides/iprotectionmanager/check_write_protection/#str) | Megállapítja, hogy egy prezentáció jelszóval védett-e a módosításhoz. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)