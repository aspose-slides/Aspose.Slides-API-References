---
title: FromArgb()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří instanci třídy Color, která představuje zadanou barvu.
type: docs
weight: 235
url: /cs/system.drawing/color/fromargb/
---
## Color::FromArgb(int) metoda

Vytvoří instanci třídy [Color](../), která představuje zadanou barvu.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| argb | int | 32bitová hodnota ARGB barvy, kterou bude představovat vytvářený objekt |

### Návratová hodnota

Objekt, který představuje zadanou barvu.

## Color::FromArgb(int, int, int, int) metoda

Vytvoří instanci třídy [Color](../), která představuje zadanou barvu.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | int | Hodnota alfa komponenty barvy |
| red | int | Hodnota červené složky barvy |
| green | int | Hodnota zelené složky barvy |
| blue | int | Hodnota modré složky barvy |

### Návratová hodnota

Objekt, který představuje zadanou barvu.

## Color::FromArgb(int, int, int) metoda

Vytvoří instanci třídy [Color](../), která představuje zadanou barvu s alfa komponentou nastavenou na 0xFF.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| red | int | Hodnota červené složky barvy |
| green | int | Hodnota zelené složky barvy |
| blue | int | Hodnota modré složky barvy |

### Návratová hodnota

Objekt, který představuje zadanou barvu.

## Color::FromArgb(int, Color) metoda

Vytvoří instanci třídy [Color](../), která představuje zadanou barvu.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | int | Hodnota alfa komponenty barvy |
| base_color | [Color](../) | instance objektu [Color](../), který představuje červenou, zelenou a modrou složky barvy, kterou bude představovat vytvářený objekt |

### Návratová hodnota

Objekt, který představuje zadanou barvu.

## Viz také

* Třída [Color](../)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)