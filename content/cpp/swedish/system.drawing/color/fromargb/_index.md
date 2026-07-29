---
title: FromArgb()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans av Color-klassen som representerar den angivna färgen.
type: docs
weight: 235
url: /sv/system.drawing/color/fromargb/
---
## Color::FromArgb(int) metod

Skapar en instans av klassen [Color](../) som representerar den angivna färgen.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int | Ett 32-bitars ARGB-värde för färgen som ska representeras av det objekt som konstrueras |

### Returvärde

Ett objekt som representerar den angivna färgen.

## Color::FromArgb(int, int, int, int) metod

Skapar en instans av klassen [Color](../) som representerar den angivna färgen.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | int | Ett värde för alfakomponenten i färgen |
| red | int | Ett värde för den röda komponenten i färgen |
| green | int | Ett värde för den gröna komponenten i färgen |
| blue | int | Ett värde för den blå komponenten i färgen |

### Returvärde

Ett objekt som representerar den angivna färgen.

## Color::FromArgb(int, int, int) metod

Skapar en instans av klassen [Color](../) som representerar den angivna färgen med alfakomponenten satt till 0xFF.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| red | int | Ett värde för den röda komponenten i färgen |
| green | int | Ett värde för den gröna komponenten i färgen |
| blue | int | Ett värde för den blå komponenten i färgen |

### Returvärde

Ett objekt som representerar den angivna färgen.

## Color::FromArgb(int, Color) metod

Skapar en instans av klassen [Color](../) som representerar den angivna färgen.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | int | Ett värde för alfakomponenten i färgen |
| base_color | [Color](../) | En instans av objektet [Color](../) som representerar de röda, gröna och blå komponenterna i färgen som ska representeras av det objekt som skapas |

### Returvärde

Ett objekt som representerar den angivna färgen.

## Se även

* Klass [Color](../)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)