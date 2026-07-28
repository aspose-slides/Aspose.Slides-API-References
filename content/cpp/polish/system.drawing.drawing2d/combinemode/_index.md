---
title: CombineMode
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, w jaki sposób regiony przycinania są łączone.
type: docs
weight: 170
url: /pl/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Określa, w jaki sposób regiony przycinania są łączone.

```cpp
enum class CombineMode
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Replace | 0 | Jeden region przycinania jest zastępowany przez inny. |
| Intersect | 1 | Dwa regiony przycinania są łączone poprzez wzięcie ich przecięcia. |
| Union | 2 | Dwa regiony przycinania są łączone poprzez wzięcie ich sumy. |
| Xor | 3 | Dwa regiony przycinania są łączone, wybierając jedynie obszar obejmowany przez jeden z regionów, ale nie oba. |
| Exclude | 4 | Dwa regiony przycinania są łączone, wybierając obszar pierwszego regionu, który nie pokrywa się z drugim. |
| Complement | 5 | Dwa regiony przycinania są łączone, wybierając obszar drugiego regionu, który nie pokrywa się z pierwszym. |

## Zobacz także

* Przestrzeń nazw [System::Drawing::Drawing2D](../)
* Biblioteka [Aspose.Slides](../../)