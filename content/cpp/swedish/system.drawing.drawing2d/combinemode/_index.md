---
title: CombineMode
second_title: Aspose.Slides för C++ API-referens
description: Anger hur beskärningsregioner kombineras.
type: docs
weight: 170
url: /sv/system.drawing.drawing2d/combinemode/
---
## CombineMode enum

Anger hur beskärningsregioner kombineras.

```cpp
enum class CombineMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Replace | 0 | En beskärningsregion ersätts av en annan. |
| Intersect | 1 | De två beskärningsregionerna kombineras genom att ta deras skärningsmängd. |
| Union | 2 | De två beskärningsregionerna kombineras genom att ta unionen av båda. |
| Xor | 3 | De två beskärningsregionerna kombineras genom att ta endast området som omsluts av den ena eller den andra regionen, men inte båda. |
| Exclude | 4 | Två beskärningsregioner kombineras genom att ta området av den första regionen som inte skär med den andra. |
| Complement | 5 | Två beskärningsregioner kombineras genom att ta området av den andra regionen som inte skär med den första. |

## Se även

* Namnrymd [System::Drawing::Drawing2D](../)
* Bibliotek [Aspose.Slides](../../)