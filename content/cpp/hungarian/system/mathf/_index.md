---
title: MathF
second_title: Aspose.Slides C++ API referenciája
description: Matematikai függvényeket tartalmaz egyszeres pontosságú lebegőpontos értékekhez. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányokat ebből semmilyen módon.
type: docs
weight: 1795
url: /hu/system/mathf/
---
## MathF struct

Matematikai függvényeket tartalmaz egyszeres pontosságú lebegőpontos értékekhez. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányokat ebből semmilyen módon.

```cpp
class MathF
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static T [Abs](./abs/)(T) | Visszaadja a megadott érték abszolút értékét. |
| static **float** [Acos](./acos/)(**float**) | Kiszámítja a megadott érték arkusz koszinuszát. |
| static **float** [Asin](./asin/)(**float**) | Kiszámítja a megadott érték arkusz szinuszát. |
| static **float** [Atan](./atan/)(**float**) | Kiszámítja a megadott érték arkusz tangensét. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Kiszámítja a megadott értékek arányának arkusz tangensét. |
| static **float** [Ceiling](./ceiling/)(**float**) | Visszaadja a legkisebb egész értéket, amely nagyobb vagy egyenlő a megadott értéknél. |
| static **float** [Cos](./cos/)(**float**) | Kiszámítja a megadott érték koszinuszát. |
| static **float** [Cosh](./cosh/)(**float**) | Kiszámítja a megadott érték hiperbolikus koszinuszát. |
| static **float** [Exp](./exp/)(**float**) | Visszaadja az e állandó megadott hatványra emelését. |
| static **float** [Floor](./floor/)(**float**) | Visszaadja a legnagyobb egész értéket, amely kisebb vagy egyenlő a megadott értéknél. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Visszaadja a maradékot, amely a megadott szám egy másik megadott számmal való osztásából származik. |
| static **float** [Log](./log/)(**float**) | Visszaadja a megadott érték természetes logaritmusát. |
| static **float** [Log](./log/)(**float**, **float**) | Visszaadja a megadott érték logaritmusát a megadott alapon. |
| static **float** [Log10](./log10/)(**float**) | Visszaadja a megadott érték 10-es alapú logaritmusát. |
| static **float** [Pow](./pow/)(**float**, **float**) | Visszaadja a megadott érték megadott hatványra emelését. |
| static **float** [Round](./round/)(**float**) | Kerekíti a megadott értéket a legközelebbi egész értékre. |
| static **float** [Round](./round/)(**float**, int) | Kerekíti a megadott értéket a legközelebbi értékre a megadott számú tizedesjeggyel. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a legközelebbi egész számra. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyaránt távolságban van a két legközelebbi számhoz. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a legközelebbi értékre a megadott számú tizedesjeggyel. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyaránt távolságban van a két legközelebbi számhoz. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a legközelebbi értékre a megadott számú tizedesjeggyel. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyaránt távolságban van a két legközelebbi számhoz. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Meghatározza a megadott előjeles egész érték előjelét. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Meghatározza a megadott lebegőpontos érték előjelét. |
| static **float** [Sin](./sin/)(**float**) | Kiszámítja a megadott érték szinuszát. |
| static **float** [Sinh](./sinh/)(**float**) | Kiszámítja a megadott érték hiperbolikus szinuszát. |
| static **float** [Sqrt](./sqrt/)(**float**) | Visszaadja a megadott érték négyzetgyökét. |
| static **float** [Tan](./tan/)(**float**) | Kiszámítja a megadott érték tangensét. |
| static **float** [Tanh](./tanh/)(**float**) | Kiszámítja a megadott érték hiperbolikus tangensét. |
| static **float** [Truncate](./truncate/)(**float**) | Visszaad egy egyszeres pontosságú lebegőpontos értéket, amelynek egész része megegyezik a megadott értékével, és a törtjegyek el lettek vetve. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [E](./e/) | A természetes logaritmus alapszáma. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | A Pi szám állandója. |
| static [Tau](./tau/) | Tau érték. |

## Lásd még

* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)