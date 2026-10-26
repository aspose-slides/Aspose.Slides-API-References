---
title: Zip64Mode
second_title: Aspose.Slides for C++ API referencia
description: Megadja, hogy mikor kell használni a ZIP64 formátum kiterjesztéseket az OpenXML fájlhoz.
type: docs
weight: 1119
url: /hu/aspose.slides.export/zip64mode/
---
## Zip64Mode felsorolat

Megadja, hogy mikor használjon ZIP64 formátum kiterjesztéseket az OpenXML fájlhoz.

```cpp
enum class Zip64Mode
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Never | 0 | Ne használjon ZIP64 formátum kiterjesztéseket. |
| IfNecessary | 1 | Használja a ZIP64 formátum kiterjesztéseket, ha szükséges. |
| Always | 2 | Mindig használja a ZIP64 formátum kiterjesztéseket. |

## Megjegyzések

Az OpenXML fájl egy ZIP-archívum, amelynek 4 GB (2^32 bájt) korlátja van a fájl tömörítetlen méretére, a fájl tömörített méretére és az archívum teljes méretére, valamint 65 535 (2^16-1) fájlra korlátozódik az archívumban. A ZIP64 formátum kiterjesztések növelik a korlátokat 2^64-re. 
## Lásd még

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)