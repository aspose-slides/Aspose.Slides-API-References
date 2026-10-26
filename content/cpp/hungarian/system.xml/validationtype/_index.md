---
title: ValidationType
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a végrehajtandó ellenőrzés típusát.
type: docs
weight: 729
url: /hu/system.xml/validationtype/
---
## ValidationType enum

Megadja a végrehajtandó ellenőrzés típusát.

```cpp
enum class ValidationType
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Nem történik ellenőrzés, és nem dobódik ellenőrzési hiba. Ez a beállítás egy XML 1.0 kompatibilis, nem ellenőrző elemzőt hoz létre. |
| Auto | 1 | Ellenőrzést hajt végre, ha DTD vagy séma információ található. |
| DTD | 2 | Az DTD szerint ellenőrzést végez. |
| XDR | 3 | Az XML-Data Reduced (XDR) sémák szerint ellenőrzést végez, beleértve a beágyazott XDR sémákat is. Az XDR sémákat a **x-schema** névtér előtag vagy a [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) érték alapján ismeri fel. |
| Schema | 4 | Az XML [Schema](../../system.xml.schema/) definíciós nyelv (XSD) sémái szerint ellenőrzést végez, beleértve a beágyazott XML sémákat is. Az XML sémákat a névtér URI-kkel a **schemaLocation** attribútum vagy a megadott **Schemas** segítségével kapcsolják össze. |

## Lásd még

* Névtere [System::Xml](../)
* Könyvtár [Aspose.Slides](../../)