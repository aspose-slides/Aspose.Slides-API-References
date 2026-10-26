---
title: SpecifyKind()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový objekt DateTime, který představuje stejný počet tiků jako zadaný objekt DateTime a představuje místní čas, UTC čas nebo žádný, jak je určeno argumentem kind.
type: docs
weight: 833
url: /cs/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) metoda

Vytvoří nový objekt [DateTime](../), který představuje stejný počet tiků jako zadaný objekt [DateTime](../) a představuje místní čas, UTC čas nebo žádný, jak je určeno argumentem **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [DateTime](../) | Objekt [DateTime](../) ze kterého se kopíruje počet tiků |
| kind | [DateTimeKind](../../datetimekind/) | Určuje, zda má nový objekt představovat místní čas, UTC čas nebo žádný. |

### Návratová hodnota

Nový objekt [DateTime](../), který představuje stejný počet tiků jako **value** a hodnotu DateTimeKind určenou pomocí **kind**.

## Viz také

* Výčet [DateTimeKind](../../datetimekind/)
* Třída [DateTime](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)