---
title: get_Encoding()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja az XML-dokumentum kódolási szintjét.
type: docs
weight: 14
url: /hu/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() metódus


Visszaadja az XML-dokumentum kódolási szintjét.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### Visszatérési érték

Az érvényes karakterkódolás neve.
## Megjegyzés



Az XML leggyakrabban támogatott karakterkódolás-nevei a következők: 

| Kategória | Kódolás nevei |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |


Ez az érték opcionális. Ha nincs beállítva, ez a metódus [String::Empty](../../../system/string/empty/)-t ad vissza. Ha nincs megadva kódolási attribútum, UTF-8 kódolást feltételez a dokumentum írásakor vagy mentésekor. 
## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlDeclaration](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)