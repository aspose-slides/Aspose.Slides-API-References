---
title: AddPie()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Dodaje określony obrys kształtu wycinka koła do ścieżki reprezentowanej przez bieżący obiekt.
type: docs
weight: 209
url: /pl/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) metoda

Dodaje określony obrys wycinka koła do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X lewego górnego rogu prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| y | **float** | Współrzędna Y lewego górnego rogu prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| width | **float** | Szerokość prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| height | **float** | Wysokość prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| startAngle | **float** | Określa początkowy kąt wycinka koła w stopniach, mierzony zgodnie z ruchem wskazówek zegara od osi X |
| sweepAngle | **float** | Określa kąt pomiędzy początkowym kątem a końcem wycinka koła |

## GraphicsPath::AddPie(int, int, int, int, float, float) metoda

Dodaje określony obrys wycinka koła do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | int | Współrzędna X lewego górnego rogu prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| y | int | Współrzędna Y lewego górnego rogu prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| width | int | Szerokość prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| height | int | Wysokość prostokąta, który ogranicza elipsę, z której rysowany jest wycinek koła |
| startAngle | **float** | Określa początkowy kąt wycinka koła w stopniach, mierzony zgodnie z ruchem wskazówek zegara od osi X |
| sweepAngle | **float** | Określa kąt pomiędzy początkowym kątem a końcem wycinka koła |

## GraphicsPath::AddPie(const Rectangle\&, float, float) metoda

Dodaje określony obrys wycinka koła do ścieżki reprezentowanej przez bieżący obiekt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Prostokąt, który ogranicza elipsę, z której rysowany jest wycinek koła |
| startAngle | **float** | Określa początkowy kąt wycinka koła w stopniach, mierzony zgodnie z ruchem wskazówek zegara od osi X |
| sweepAngle | **float** | Określa kąt pomiędzy początkowym kątem a końcem wycinka koła |

## Zobacz także

* Klasa [GraphicsPath](../)
* Klasa [Rectangle](../../../system.drawing/rectangle/)
* Przestrzeń nazw [System::Drawing::Drawing2D](../../)
* Biblioteka [Aspose.Slides](../../../)