---
title: FromArgb()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy instancję klasy Color, która reprezentuje określony kolor.
type: docs
weight: 235
url: /pl/system.drawing/color/fromargb/
---
## Color::FromArgb(int) metoda

Tworzy instancję klasy [Color](../), która reprezentuje określony kolor.

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| argb | int | 32-bitowa wartość ARGB koloru, który ma być reprezentowany przez tworzony obiekt |

### Wartość zwracana

Obiekt, który reprezentuje określony kolor.

## Color::FromArgb(int, int, int, int) metoda

Tworzy instancję klasy [Color](../), która reprezentuje określony kolor.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| alpha | int | Wartość składnika alfa koloru |
| red | int | Wartość składnika czerwonego koloru |
| green | int | Wartość składnika zielonego koloru |
| blue | int | Wartość składnika niebieskiego koloru |

### Wartość zwracana

Obiekt, który reprezentuje określony kolor.

## Color::FromArgb(int, int, int) metoda

Tworzy instancję klasy [Color](../), która reprezentuje określony kolor z ustawionym składnikiem alfa na 0xFF.

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| red | int | Wartość składnika czerwonego koloru |
| green | int | Wartość składnika zielonego koloru |
| blue | int | Wartość składnika niebieskiego koloru |

### Wartość zwracana

Obiekt, który reprezentuje określony kolor.

## Color::FromArgb(int, Color) metoda

Tworzy instancję klasy [Color](../), która reprezentuje określony kolor.

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| alpha | int | Wartość składnika alfa koloru |
| base_color | [Color](../) | Instancja obiektu [Color](../), który reprezentuje komponenty czerwonego, zielonego i niebieskiego koloru, które mają być reprezentowane przez tworzony obiekt |

### Wartość zwracana

Obiekt, który reprezentuje określony kolor.

## Zobacz także

* Klasa [Color](../)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)