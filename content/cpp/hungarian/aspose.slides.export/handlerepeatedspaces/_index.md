---
title: HandleRepeatedSpaces
second_title: Aspose.Slides C++ API referenciája
description: Megadja, hogyan kell kezelni a többszörös szabályos szóköz karaktereket a Markdown exportálás során.
type: docs
weight: 937
url: /hu/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Specifies how repeated regular space characters should be handled during Markdown export.

```cpp
enum class HandleRepeatedSpaces
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| None | 0 | Az összes szóköz változtatás nélkül megmarad rendszeres szóköz karakterként. Nem történik átalakítás, és a többször egymás után következő szóközök változatlanul kerülnek exportálásra. |
| AlternateSpacesToNbsp | 1 | A két vagy több egymás utáni rendszeres szóköz sorozatát úgy alakítja, hogy felváltva használ rendszeres szóköz karaktereket és nem törő szóköz entitásokat (**&nbsp;**). Az első szóköz mindig rendszeres szóközként marad. |
| MultipleSpacesToNbsp | 2 | A két vagy több egymás utáni rendszeres szóköz sorozatát úgy alakítja, hogy az első szóköz megmarad rendszeres szóköz karakterként, a további szóközöket pedig nem törő szóköz entitásokkal (**&nbsp;**) helyettesíti. |

## Lásd még

* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)