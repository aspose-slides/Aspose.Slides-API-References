---
title: Round()
second_title: Aspose.Slides C++ API Referenciája
description: Kerekíti a megadott értéket a legközelebbi egész számra. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel áll a két legközelebbi számhoz.
type: docs
weight: 404
url: /hu/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) metódus

Kerekíti a megadott értéket a legközelebbi egész számra. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | const [Decimal](../)\& | A kerekítendő érték |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell elvégezni a kerekítést, ha a **value** egyformán közel van a két legközelebbi számhoz. |

### Return Value

**d** a legközelebbi egész értékre kerekítve

## Decimal::Round(const Decimal\&, int, MidpointRounding) metódus

Kerekíti a megadott értéket a legközelebbi olyan értékre, amely a megadott számú tizedesjegyet tartalmazza. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | const [Decimal](../)\& | A kerekítendő érték |
| digits | int | A kerekített értékben szereplő tizedesjegyek száma |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell elvégezni a kerekítést, ha a **value** egyformán közel van a két legközelebbi számhoz. |

### Return Value

A megadott számú jeggyel rendelkező szám, amely a **value**-hoz legközelebb áll

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)