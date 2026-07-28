---
title: Round()
second_title: Aspose.Slides C++ API referencia
description: Kerekíti a megadott értéket a legközelebbi egész értékre.
type: docs
weight: 157
url: /hu/system/mathf/round/
---
## MathF::Round(float) metódus

Kerekíti a megadott értéket a legközelebbi egész értékre.

```cpp
static float System::MathF::Round(float a)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | **float** | A kerekítendő érték |

### Visszatérési érték

**a** a legközelebbi egész értékre kerekítve

## MathF::Round(float, int) metódus

Kerekíti a megadott értéket a legközelebbi értékre a megadott számú tizedesjegy pontossággal.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **float** | A kerekítendő érték |
| digits | int | A kerekített értékben lévő törtjegyek száma |

### Visszatérési érték

A **value**-hez legközelebbi szám a megadott számú jeggyel

## MathF::Round(float, MidpointRounding) metódus

Kerekíti a megadott értéket a legközelebbi egész számra. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyenlő távolságra van a két legközelebbi számtól.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **float** | A kerekítendő érték |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell elvégezni a kerekítést, ha a **value** egyenlő távolságra van a két legközelebbi számtól. |

### Visszatérési érték

**value** a legközelebbi egész értékre kerekítve

## MathF::Round(float, int, MidpointRounding) metódus

Kerekíti a megadott értéket a legközelebbi értékre a megadott számú törtjeggyel. Egy paraméter határozza meg a függvény viselkedését, ha a megadott érték egyenlő távolságra van a két legközelebbi számtól.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **float** | A kerekítendő érték |
| digits | int | A kerekített értékben lévő törtjegyek száma |
| mode | [MidpointRounding](../../midpointrounding/) | Megadja, hogyan kell elvégezni a kerekítést, ha a **value** egyenlő távolságra van a két legközelebbi számtól. |

### Visszatérési érték

A **value**-hez legközelebbi szám a megadott számú jeggyel

## Lásd még

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)