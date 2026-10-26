---
title: CombineMode
second_title: Aspose.Slides for C++ API Referencia
description: Meghatározza, hogyan kombinálódnak a vágási területek.
type: docs
weight: 170
url: /hu/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Megadja, hogyan kombinálódnak a vágási területek.

```cpp
enum class CombineMode
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| Replace | 0 | Egy vágási területet egy másik helyettesít. |
| Intersect | 1 | A két vágási területet a metszetük képzésével kombinálják. |
| Union | 2 | A két vágási területet az uniójuk képzésével kombinálják. |
| Xor | 3 | A két vágási területet úgy kombinálják, hogy csak az egyiket vagy a másikat körülvevő területet veszik, de nem mindkettőt. |
| Exclude | 4 | A két vágási területet úgy kombinálják, hogy az első terület azon részét veszik, ami nem metszi a másodikat. |
| Complement | 5 | A két vágási területet úgy kombinálják, hogy a második terület azon részét veszik, ami nem metszi az elsőt. |

## Lásd még

* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)