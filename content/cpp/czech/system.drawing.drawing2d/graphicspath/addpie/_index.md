---
title: AddPie()
second_title: Aspose.Slides pro C++ - reference API
description: Přidá specifikovaný obrys tvaru výseče do cesty reprezentované aktuálním objektem.
type: docs
weight: 209
url: /cs/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) metoda


Přidá specifikovaný obrys tvaru výseče do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Souřadnice X levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| y | **float** | Souřadnice Y levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| width | **float** | Šířka levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| height | **float** | Výška levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| startAngle | **float** | Určuje úvodní úhel výseče ve stupních, měřený po směru hodinových ručiček od osy X |
| sweepAngle | **float** | Určuje úhel mezi úvodním úhlem a koncem výseče |

## GraphicsPath::AddPie(int, int, int, int, float, float) metoda


Přidá specifikovaný obrys tvaru výseče do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | int | Souřadnice X levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| y | int | Souřadnice Y levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| width | int | Šířka levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| height | int | Výška levého horního rohu obdélníku, který ohraničuje elipsu, ze které je výseč kreslena |
| startAngle | **float** | Určuje úvodní úhel výseče ve stupních, měřený po směru hodinových ručiček od osy X |
| sweepAngle | **float** | Určuje úhel mezi úvodním úhlem a koncem výseče |

## GraphicsPath::AddPie(const Rectangle\&, float, float) metoda


Přidá specifikovaný obrys tvaru výseče do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Obdélník, který ohraničuje elipsu, ze které je výseč kreslena |
| startAngle | **float** | Určuje úvodní úhel výseče ve stupních, měřený po směru hodinových ručiček od osy X |
| sweepAngle | **float** | Určuje úhel mezi úvodním úhlem a koncem výseče |

## Viz také

* Třída [GraphicsPath](../)
* Třída [Rectangle](../../../system.drawing/rectangle/)
* Jmenný prostor [System::Drawing::Drawing2D](../../)
* Knihovna [Aspose.Slides](../../../)