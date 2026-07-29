---
title: Rectangle()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av Rectangle-objektet som representerar en rektangel med X- och Y-koordinater samt bredd- och höjdvärden satta till 0.
type: docs
weight: 1
url: /sv/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() konstruktor

Skapar en ny instans av [Rectangle](../)-objektet som representerar en rektangel med X- och Y-koordinater samt bredd- och höjdvärden satta till 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) konstruktor

Skapar en ny instans av [Rectangle](../)-objektet som representerar en rektangel med de angivna koordinaterna för dess övre vänstra hörn samt bredd och höjd.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Ett värde för X-koordinaten för rektangelns övre vänstra hörn |
| y | int | Ett värde för Y-koordinaten för rektangelns övre vänstra hörn |
| width | int | Rektangelns bredd |
| height | int | Rektangelns höjd |

## Rectangle::Rectangle(const Point\&, const Size\&) konstruktor

Skapar en ny instans av [Rectangle](../)-objektet som representerar en rektangel med koordinaterna för dess övre vänstra hörn angivna som en instans av klassen [Point](../../point/) och dess bredd och höjd som en instans av klassen [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Anger platsen för rektangelns övre vänstra hörn |
| size | const [Size](../../size/)\& | Anger rektangelns bredd och höjd |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) konstruktor

Skapar en ny instans av [Rectangle](../)-objektet som representerar den rektangel som motsvarar den angivna.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | En instans av **System::Windows::Forms::Screen::Rectangle_**-klassen som specificerar positionen och storleken på rektangeln som ska representeras av det konstruerade objektet |

## Se också

* Klass [Rectangle](../)
* Klass [Point](../../point/)
* Klass [Size](../../size/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)