---
title: IPresentationInfo class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/ipresentationinfo/
---
## IPresentationInfo osztály

Információ a prezentációfájlról

The IPresentationInfo type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`is_encrypted`](/slides/python-net/hu/aspose.slides/ipresentationinfo/is_encrypted/) | True-t ad vissza, ha a kötött prezentáció titkosított, egyébként False.<br/>            Csak olvasható **bool**. |
| [`is_password_protected`](/slides/python-net/hu/aspose.slides/ipresentationinfo/is_password_protected/) | Értéket ad vissza, amely azt jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz. |
| [`is_write_protected`](/slides/python-net/hu/aspose.slides/ipresentationinfo/is_write_protected/) | Értéket ad vissza, amely azt jelzi, hogy a kötött prezentáció írásvédett-e. |
| [`load_format`](/slides/python-net/hu/aspose.slides/ipresentationinfo/load_format/) | A kötött prezentáció formátumát adja vissza.<br/>            Csak olvasható [`LoadFormat`](/slides/python-net/hu/aspose.slides/loadformat). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/hu/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | A kötött prezentációt streambe írja. |
| [`write_binded_presentation(self, file)`](/slides/python-net/hu/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | A kötött prezentációt fájlba írja. |
| [`check_password(self, password)`](/slides/python-net/hu/aspose.slides/ipresentationinfo/check_password/#str) | Ellenőrzi, hogy a jelszó helyes-e a megnyitás jelszóval védett prezentációhoz. |
| [`check_write_protection(self, password)`](/slides/python-net/hu/aspose.slides/ipresentationinfo/check_write_protection/#str) | Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentáció esetén. |
| [`read_document_properties(self)`](/slides/python-net/hu/aspose.slides/ipresentationinfo/read_document_properties/#) | A kötött prezentáció dokumentum-tulajdonságait adja vissza. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/hu/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | A kötött prezentáció tulajdonságait frissíti. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)