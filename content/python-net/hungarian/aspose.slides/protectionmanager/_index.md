---
title: ProtectionManager class
second_title: Aspose.Slides a Python számára .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/protectionmanager/
---
## ProtectionManager osztály

A prezentáció jelszóvédelmének kezelése.

A ProtectionManager típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/hu/aspose.slides/protectionmanager/encrypt_document_properties/) | Ez a tulajdonság értelmes, ha a bemutató jelszóval védett.<br/>            Ha igaz, akkor a dokumentum tulajdonságok a bemutató fájlban titkosítottak.<br/>            Ha hamis, akkor a dokumentum tulajdonságok nyilvánosak, míg a bemutató titkosított.<br/>            Olvasás/írás **bool**. |
| [`is_encrypted`](/slides/python-net/hu/aspose.slides/protectionmanager/is_encrypted/) | Visszaad egy értéket, amely jelzi, hogy ez a példány titkosított-e.<br/>            Csak-olvasás **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/hu/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Ez a tulajdonság értelmes, ha a prezentáció fájl jelszóval védett, és a dokumentum <br/>            tulajdonságai ennek a fájlnak nyilvánosak.<br/>            Az igaz érték azt jelenti, hogy csak a dokumentum tulajdonságai töltődnek be egy titkosított <br/>            prezentáció fájlból jelszó használata nélkül.<br/>            A hamis érték azt jelenti, hogy a teljes titkosított prezentáció betöltődik a helyes <br/>            jelszó használatával, nem csak a dokumentum tulajdonságai.<br/>            Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig hamis.<br/>            Ha egy titkosított fájl dokumentum tulajdonságai nincsenek nyilvánosak, akkor a tulajdonság értéke mindig hamis.<br/>            Ha a Presentation.EncryptDocumentProperties igaz, akkor az IsOnlyDocumentPropertiesLoaded <br/>            tulajdonság értéke mindig hamis.<br/>            Csak-olvasás **bool**. |
| [`is_write_protected`](/slides/python-net/hu/aspose.slides/protectionmanager/is_write_protected/) | Visszaad egy értéket, amely jelzi, hogy ez a prezentáció írásvédett-e.<br/>            Csak-olvasás **bool**. |
| [`encryption_password`](/slides/python-net/hu/aspose.slides/protectionmanager/encryption_password/) | Visszaadja a prezentáció titkosításához használt jelszót.<br/>            Csak-olvasás **str**. |
| [`read_only_recommended`](/slides/python-net/hu/aspose.slides/protectionmanager/read_only_recommended/) | Visszaadja vagy beállítja a csak-olvasás ajánlást.<br/>            Olvasás/írás **bool**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/hu/aspose.slides/protectionmanager/encrypt/#str) | Titkosítja a prezentációt a megadott jelszóval. |
| [`remove_encryption(self)`](/slides/python-net/hu/aspose.slides/protectionmanager/remove_encryption/#) | Eltávolítja a titkosítást. |
| [`set_write_protection(self, password)`](/slides/python-net/hu/aspose.slides/protectionmanager/set_write_protection/#str) | Beállítja a írásvédelmet ehhez a prezentációhoz a megadott jelszóval. |
| [`remove_write_protection(self)`](/slides/python-net/hu/aspose.slides/protectionmanager/remove_write_protection/#) | Eltávolítja a írásvédelmet ebből a prezentációból. |
| [`check_write_protection(self, password)`](/slides/python-net/hu/aspose.slides/protectionmanager/check_write_protection/#str) | Megállapítja, hogy a prezentáció jelszóval védett-e módosításhoz. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)