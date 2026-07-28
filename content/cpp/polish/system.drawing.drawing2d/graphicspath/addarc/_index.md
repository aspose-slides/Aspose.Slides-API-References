---
title: AddArc()
second_title: Referencja API Aspose.Slides dla C++
description: Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt.
type: docs
weight: 183
url: /pl/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) metoda


Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| y | **float** | Współrzędna Y lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| width | **float** | Szerokość lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| height | **float** | Wysokość lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| startAngle | **float** | Określa początkowy kąt łuku w stopniach, mierzony w kierunku zgodnym z ruchem wskazówek zegara od osi X |
| sweepAngle | **float** | Określa kąt pomiędzy początkowym kątem a końcem łuku |

## GraphicsPath::AddArc(int, int, int, int, float, float) metoda


Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | int | Współrzędna X lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| y | int | Współrzędna Y lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| width | int | Szerokość lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| height | int | Wysokość lewego górnego rogu prostokąta ograniczającego elipsę, z której rysowany jest łuk |
| startAngle | **float** | Określa początkowy kąt łuku w stopniach, mierzony w kierunku zgodnym z ruchem wskazówek zegara od osi X |
| sweepAngle | **float** | Określa kąt pomiędzy początkowym kątem a końcem łuku |

## GraphicsPath::AddArc(const RectangleF\&, float, float) metoda


Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | Prostokąt ograniczający elipsę, z której rysowany jest łuk |
| startAngle | **float** | Określa początkowy kąt łuku w stopniach, mierzony w kierunku zgodnym z ruchem wskazówek zegara od osi X |
| sweepAngle | **float** | Określa kąt pomiędzy początkowym kątem a końcem łuku |

## GraphicsPath::AddArc(const Rectangle\&, float, float) metoda


Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Prostokąt ograniczający elipsę, z której rysowany jest łuk |
| startAngle | **float** | Określa początkowy kąt łuku w stopniach, mierzony w kierunku zgodnym z ruchem wskazówek zegara od osi X |
| sweepAngle | **float** | Określa kąt pomiędzy początkowym kątem a końcem łuku |

## Zobacz także

* Klasa [GraphicsPath](../)
* Klasa [RectangleF](../../../system.drawing/rectanglef/)
* Klasa [Rectangle](../../../system.drawing/rectangle/)
* Przestrzeń nazw [System::Drawing::Drawing2D](../../)
* Biblioteka [Aspose.Slides](../../../)