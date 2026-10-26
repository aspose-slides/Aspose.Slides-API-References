---
title: CombineMode
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft aan hoe knipgebieden worden gecombineerd.
type: docs
weight: 170
url: /nl/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Geeft aan hoe knipgebieden worden gecombineerd.

```cpp
enum class CombineMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Replace | 0 | Een knipgebied wordt vervangen door een ander. |
| Intersect | 1 | De twee knipgebieden worden gecombineerd door hun intersectie te nemen. |
| Union | 2 | De twee knipgebieden worden gecombineerd door de unie van beiden te nemen. |
| Xor | 3 | De twee knipgebieden worden gecombineerd door alleen het gebied te nemen dat door één van de beide gebieden omsloten wordt, maar niet door beide. |
| Exclude | 4 | Twee knipgebieden worden gecombineerd door het gebied van het eerste gebied te nemen dat niet overlapt met het tweede. |
| Complement | 5 | Twee knipgebieden worden gecombineerd door het gebied van het tweede gebied te nemen dat niet overlapt met het eerste. |

## Zie ook

* Naamruimte [System::Drawing::Drawing2D](../)
* Bibliotheek [Aspose.Slides](../../)