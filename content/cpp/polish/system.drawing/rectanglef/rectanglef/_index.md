---
title: RectangleF()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową instancję obiektu RectangleF, który reprezentuje prostokąt z współrzędnymi X i Y oraz wartościami szerokości i wysokości ustawionymi na 0.
type: docs
weight: 1
url: /pl/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() konstruktor


Tworzy nową instancję obiektu [RectangleF](../), który reprezentuje prostokąt z współrzędnymi X i Y oraz wartościami szerokości i wysokości ustawionymi na 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) konstruktor


Tworzy nową instancję obiektu [RectangleF](../), który reprezentuje prostokąt o podanych współrzędnych lewego górnego rogu oraz szerokości i wysokości.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Wartość współrzędnej X lewego górnego rogu prostokąta |
| y | **float** | Wartość współrzędnej Y lewego górnego rogu prostokąta |
| width | **float** | Szerokość prostokąta |
| height | **float** | Wysokość prostokąta |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) konstruktor


Tworzy nową instancję obiektu [RectangleF](../), który reprezentuje prostokąt, którego współrzędne lewego górnego rogu są określone jako instancja klasy [PointF](../../pointf/), a jego szerokość i wysokość jako instancja klasy [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Określa położenie lewego górnego rogu prostokąta |
| size | const [SizeF](../../sizef/)\& | Określa szerokość i wysokość prostokąta |

## RectangleF::RectangleF(const Rectangle\&) konstruktor


Tworzy nową instancję obiektu [RectangleF](../), który reprezentuje prostokąt równoważny podanemu.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Instancja klasy [Rectangle](../../rectangle/) określająca pozycję i rozmiar prostokąta, który ma być reprezentowany przez tworzony obiekt |

## Zobacz także

* Klasa [RectangleF](../)
* Klasa [PointF](../../pointf/)
* Klasa [SizeF](../../sizef/)
* Klasa [Rectangle](../../rectangle/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)