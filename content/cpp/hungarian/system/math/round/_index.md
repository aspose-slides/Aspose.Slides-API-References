---
title: Round()
second_title: Aspose.Slides for C++ API-referencia
description: A megadott értéket a legközelebbi egész számra kerekíti.
type: docs
weight: 157
url: /hu/system/math/round/
---
## Math::Round(double) metódus

A megadott értéket a legközelebbi egész számra kerekíti.

```cpp
static double System::Math::Round(double a)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | **double** | A kerekítendő érték |

### Visszatérési érték

**a** a legközelebbi egész értékre kerekítve

## Math::Round(double, int) metódus

A megadott értéket a megadott számú tizedesjeggyel rendelkező legközelebbi értékre kerekíti.

```cpp
static double System::Math::Round(double value, int digits)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | A kerekítendő érték |
| digits | int | A kerekített érték tizedesjegyeinek száma |

### Visszatérési érték

A megadott számjegyek számmal legközelebb álló szám a **value**-hez

## Math::Round(double, MidpointRounding) metódus

A megadott értéket a legközelebbi egész számra kerekíti. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | A kerekítendő érték |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell végrehajtani a kerekítést, ha a **value** egyformán közel van a két legközelebbi számhoz. |

### Visszatérési érték

**value** a legközelebbi egész értékre kerekítve

## Math::Round(double, int, MidpointRounding) metódus

A megadott értéket a megadott számú tizedesjeggyel rendelkező legközelebbi értékre kerekíti. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **double** | A kerekítendő érték |
| digits | int | A kerekített érték tizedesjegyeinek száma |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell végrehajtani a kerekítést, ha a **value** egyformán közel van a két legközelebbi számhoz. |

### Visszatérési érték

A megadott számjegyek számmal legközelebb álló szám a **value**-hez

## Math::Round(const Decimal\&) metódus

A megadott értéket a legközelebbi egész számra kerekíti.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | A kerekítendő érték |

### Visszatérési érték

**d** a legközelebbi egész értékre kerekítve

## Math::Round(const Decimal\&, int) metódus

A megadott értéket a megadott számú tizedesjeggyel rendelkező legközelebbi értékre kerekíti.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | A kerekítendő érték |
| digits | int | A kerekített érték tizedesjegyeinek száma |

### Visszatérési érték

A megadott számjegyek számmal legközelebb álló szám a **value**-hez

## Math::Round(const Decimal\&, MidpointRounding) metódus

A megadott értéket a legközelebbi egész számra kerekíti. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | A kerekítendő érték |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell végrehajtani a kerekítést, ha a **value** egyformán közel van a két legközelebbi számhoz. |

### Visszatérési érték

**d** a legközelebbi egész értékre kerekítve

## Math::Round(const Decimal\&, int, MidpointRounding) metódus

A megadott értéket a megadott számú tizedesjeggyel rendelkező legközelebbi értékre kerekíti. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | A kerekítendő érték |
| digits | int | A kerekített érték tizedesjegyeinek száma |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell végrehajtani a kerekítést, ha a **value** egyformán közel van a két legközelebbi számhoz. |

### Visszatérési érték

A megadott számjegyek számmal legközelebb álló szám a **value**-hez

## Lásd még

* Enum [MidpointRounding](../../midpointrounding/)
* Osztály [Decimal](../../decimal/)
* Struct [Math](../)
* Névtere [System](../../)
* Library [Aspose.Slides](../../../)