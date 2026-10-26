---
title: FromArgb()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy példányt a Color osztályból, amely a megadott színt képviseli.
type: docs
weight: 235
url: /hu/system.drawing/color/fromargb/
---
## Color::FromArgb(int) metódus

Létrehoz egy példányt a [Color](../) osztályból, amely a megadott színt képviseli.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| argb | int | A 32 bites ARGB érték a színhez, amelyet az épített objektum képvisel |

### Visszatérési érték

Egy objektum, amely a megadott színt képviseli.

## Color::FromArgb(int, int, int, int) metódus

Létrehoz egy példányt a [Color](../) osztályból, amely a megadott színt képviseli.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | int | A szín alfa komponensének értéke |
| red | int | A szín vörös komponensének értéke |
| green | int | A szín zöld komponensének értéke |
| blue | int | A szín kék komponensének értéke |

### Visszatérési érték

Egy objektum, amely a megadott színt képviseli.

## Color::FromArgb(int, int, int) metódus

Létrehoz egy példányt a [Color](../) osztályból, amely a megadott színt képviseli, az alfa komponens értéke 0xFF.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| red | int | A szín vörös komponensének értéke |
| green | int | A szín zöld komponensének értéke |
| blue | int | A szín kék komponensének értéke |

### Visszatérési érték

Egy objektum, amely a megadott színt képviseli.

## Color::FromArgb(int, Color) metódus

Létrehoz egy példányt a [Color](../) osztályból, amely a megadott színt képviseli.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | int | A szín alfa komponensének értéke |
| base_color | [Color](../) | Egy [Color](../) objektum példánya, amely a szín vörös, zöld és kék komponenseit képviseli, amelyet a létrehozandó objektum képvisel |

### Visszatérési érték

Egy objektum, amely a megadott színt képviseli.

## Lásd még

* Osztály [Color](../)
* Névterület [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)