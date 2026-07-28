---
title: RoundImpl()
second_title: Aspose.Slides C++ API hivatkozás
description: A megadott értéket a legközelebbi értékre kerekíti a megadott számú tizedesjegy szerint. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.
type: docs
weight: 287
url: /hu/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) metódus


A megadott értéket a legközelebbi értékre kerekíti a megadott számú tizedesjegy szerint. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | A kerekítendő érték |
| digits | int | A tizedesjegyek száma a kerekített értékben |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell elvégezni a kerekítést, ha **value** egyformán közel van a két legközelebbi számhoz. |

### Visszatérési érték

A megadott számú jeggyel rendelkező szám, amely a legközelebb van **value**-hez

## Lásd még

* Enumeráció [MidpointRounding](../../midpointrounding/)
* Struktúra [MathF](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)