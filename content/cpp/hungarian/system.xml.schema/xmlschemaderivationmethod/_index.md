---
title: XmlSchemaDerivationMethod
second_title: Aspose.Slides for C++ API-referencia
description: Különböző módszereket biztosít a származtatás megakadályozására.
type: docs
weight: 1015
url: /hu/system.xml.schema/xmlschemaderivationmethod/
---
## XmlSchemaDerivationMethod enum

Különböző módszereket biztosít a származtatás megakadályozására.

```cpp
enum class XmlSchemaDerivationMethod
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Empty | 0 | Felülírja az alapértelmezett származtatási módszert, hogy bármilyen származtatást engedélyezzen. |
| Substitution | 1 | A származtatásokra hivatkozik **Substitution** segítségével. |
| Extension | 2 | A származtatásokra hivatkozik **Extension** segítségével. |
| Restriction | 4 | A származtatásokra hivatkozik **Restriction** segítségével. |
| List | 8 | A származtatásokra hivatkozik **List** segítségével. |
| Union | 16 | A származtatásokra hivatkozik **Union** segítségével. |
| All | 255 | **#all**. A származtatási módszerek mindegyikére hivatkozik. |
| None | 256 | Elfogadja az alapértelmezett származtatási módszert. |

## Lásd még

* Névterület [System::Xml::Schema](../)
* Könyvtár [Aspose.Slides](../../)