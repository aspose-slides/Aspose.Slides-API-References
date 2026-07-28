---
title: Rectangle()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nową instancję obiektu Rectangle, który reprezentuje prostokąt z współrzędnymi X i Y oraz wartościami szerokości i wysokości ustawionymi na 0.
type: docs
weight: 1
url: /pl/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() konstruktor

Tworzy nową instancję obiektu [Rectangle](../), który reprezentuje prostokąt z współrzędnymi X i Y oraz wartościami szerokości i wysokości ustawionymi na 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) konstruktor

Tworzy nową instancję obiektu [Rectangle](../), który reprezentuje prostokąt o podanych współrzędnych lewego górnego rogu oraz szerokości i wysokości.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | int | Wartość współrzędnej X lewego górnego rogu prostokąta |
| y | int | Wartość współrzędnej Y lewego górnego rogu prostokąta |
| width | int | Szerokość prostokąta |
| height | int | Wysokość prostokąta |

## Rectangle::Rectangle(const Point\&, const Size\&) konstruktor

Tworzy nową instancję obiektu [Rectangle](../), który reprezentuje prostokąt, którego współrzędne lewego górnego rogu są określone jako instancja klasy [Point](../../point/), a jego szerokość i wysokość jako instancja klasy [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Określa położenie lewego górnego rogu prostokąta |
| size | const [Size](../../size/)\& | Określa szerokość i wysokość prostokąta |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) konstruktor

Tworzy nową instancję obiektu [Rectangle](../), który reprezentuje prostokąt równoważny z podanym.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Instancja klasy **System::Windows::Forms::Screen::Rectangle_**, określająca pozycję i rozmiar prostokąta, który ma być reprezentowany przez tworzony obiekt |

## Zobacz także

* Klasa [Rectangle](../)
* Klasa [Point](../../point/)
* Klasa [Size](../../size/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)