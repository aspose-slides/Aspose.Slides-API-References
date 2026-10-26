---
title: Rectangle()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří novou instanci objektu Rectangle, který představuje obdélník se souřadnicemi X a Y a hodnotami šířky a výšky nastavenými na 0.
type: docs
weight: 1
url: /cs/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() konstruktor


Vytvoří novou instanci objektu [Rectangle](../) , který představuje obdélník se souřadnicemi X a Y a hodnotami šířky a výšky nastavenými na 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) konstruktor


Vytvoří novou instanci objektu [Rectangle](../) , který představuje obdélník se zadanými souřadnicemi levého horního rohu a šířkou a výškou.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | int | Hodnota souřadnice X levého horního rohu obdélníku |
| y | int | Hodnota souřadnice Y levého horního rohu obdélníku |
| width | int | Šířka obdélníku |
| height | int | Výška obdélníku |

## Rectangle::Rectangle(const Point\&, const Size\&) konstruktor


Vytvoří novou instanci objektu [Rectangle](../) , který představuje obdélník se souřadnicemi levého horního rohu určenými jako instance třídy [Point](../../point/) a jeho šířkou a výškou jako instance třídy [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Určuje umístění levého horního rohu obdélníku |
| size | const [Size](../../size/)\& | Určuje šířku a výšku obdélníku |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) konstruktor


Vytvoří novou instanci objektu [Rectangle](../) , který představuje obdélník ekvivalentní zadanému.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Instance třídy **System::Windows::Forms::Screen::Rectangle_**, která určuje polohu a velikost obdélníku, který má být reprezentován vytvářeným objektem |

## Viz také

* Třída [Rectangle](../)
* Třída [Point](../../point/)
* Třída [Size](../../size/)
* Jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)