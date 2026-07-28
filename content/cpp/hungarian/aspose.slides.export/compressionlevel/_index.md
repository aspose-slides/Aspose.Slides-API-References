---
title: CompressionLevel
second_title: Aspose.Slides for C++ API hivatkozás
description: Megadja a ZIP tömörítési szinteket az OpenXML fájlhoz. Magasabb szintek jobb tömörítést biztosítanak a lassabb feldolgozás árán.
type: docs
weight: 846
url: /hu/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

Megadja a ZIP tömörítési szinteket az OpenXML fájlhoz. Magasabb szintek jobb tömörítést biztosítanak, a lassabb feldolgozás árán.

```cpp
enum class CompressionLevel
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Nem alkalmaznak tömörítést. A fájlok változatlanul tárolódnak. |
| Level1 | 1 | Leggyorsabb tömörítés a legalacsonyabb tömörítési aránnyal. |
| Level2 | 2 | Gyorsabb tömörítés kissé jobb tömörítési aránnyal, mint [CompressionLevel::Level1](./). |
| Level3 | 3 | Jobb tömörítést biztosít [CompressionLevel::Level2](./)-nál, mérsékelt teljesítményhatással. |
| Level4 | 4 | Jobb tömörítést biztosít [CompressionLevel::Level3](./)-nál. |
| Level5 | 5 | [CompressionLevel::Level4](./)-nál javított tömörítést biztosít további feldolgozási idővel. |
| Level6 | 6 | Standard tömörítés, amely jó egyensúlyt kínál a tömörítési sebesség és a fájlméret között. Az alapértelmezett tömörítési szint. |
| Level7 | 7 | Magasabb tömörítést biztosít [CompressionLevel::Level6](./)-nál, lassabb feldolgozással. |
| Level8 | 8 | Magasabb tömörítést biztosít [CompressionLevel::Level7](./)-nál. |
| Level9 | 9 | Maximum tömörítés. A legkisebb fájlméretet eredményezi a leglassabb feldolgozási sebességgel. |

## Lásd még

* Névterület [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)