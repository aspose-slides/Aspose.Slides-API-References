---
title: CombineMode
second_title: Riferimento API Aspose.Slides per C++
description: Specifica come le regioni di ritaglio vengono combinate.
type: docs
weight: 170
url: /it/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Specifica come le regioni di ritaglio vengono combinate.

```cpp
enum class CombineMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Replace | 0 | Una regione di ritaglio è sostituita da un'altra. |
| Intersect | 1 | Le due regioni di ritaglio sono combinate prendendo la loro intersezione. |
| Union | 2 | Le due regioni di ritaglio sono combinate prendendo l'unione di entrambe. |
| Xor | 3 | Le due regioni di ritaglio sono combinate prendendo solo l'area racchiusa da una o l'altra regione, ma non da entrambe. |
| Exclude | 4 | Due regioni di ritaglio sono combinate prendendo l'area della prima regione che non interseca la seconda. |
| Complement | 5 | Due regioni di ritaglio sono combinate prendendo l'area della seconda regione che non interseca la prima. |

## Vedi anche

* Spazio dei nomi [System::Drawing::Drawing2D](../)
* Libreria [Aspose.Slides](../../)