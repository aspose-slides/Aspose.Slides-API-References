---
title: PresentationInfo class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/presentationinfo/
---
## PresentationInfo osztály

Információ a prezentációfájlról

A PresentationInfo típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_encrypted`](/slides/python-net/hu/aspose.slides/presentationinfo/is_encrypted/) | True-t ad, ha a kötött prezentáció titkosított, egyébként False.<br/>            Csak olvasható **bool**. |
| [`is_password_protected`](/slides/python-net/hu/aspose.slides/presentationinfo/is_password_protected/) | Egy értéket ad, amely jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz. |
| [`is_write_protected`](/slides/python-net/hu/aspose.slides/presentationinfo/is_write_protected/) | Egy értéket ad, amely jelzi, hogy a kötött prezentáció írásvédett-e. |
| [`load_format`](/slides/python-net/hu/aspose.slides/presentationinfo/load_format/) | A kötött prezentáció formátumát adja.<br/>            Csak olvasható [`LoadFormat`](/slides/python-net/hu/aspose.slides/loadformat). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/hu/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | A kötött prezentációt stream-be írja. |
| [`write_binded_presentation(self, file)`](/slides/python-net/hu/aspose.slides/presentationinfo/write_binded_presentation/#str) | A kötött prezentációt fájlba írja. |
| [`check_password(self, password)`](/slides/python-net/hu/aspose.slides/presentationinfo/check_password/#str) | Ellenőrzi, hogy a nyitó jelszóval védett prezentáció jelszava helyes-e. |
| [`check_write_protection(self, password)`](/slides/python-net/hu/aspose.slides/presentationinfo/check_write_protection/#str) | Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentáció esetén. |
| [`read_document_properties(self)`](/slides/python-net/hu/aspose.slides/presentationinfo/read_document_properties/#) | A kötött prezentáció dokumentum tulajdonságait adja. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/hu/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Frissíti a kötött prezentáció tulajdonságait. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)