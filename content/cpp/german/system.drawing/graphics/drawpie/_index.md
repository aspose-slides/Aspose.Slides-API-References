---
title: DrawPie()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeichnet das angegebene Kuchenstück mit dem angegebenen Stift auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.
type: docs
weight: 261
url: /de/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) Methode


Zeichnet das angegebene Kuchenstück mit dem angegebenen Stift auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Kuchenstücks verwendet wird |
| x | **int32_t** | Die X-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| y | **int32_t** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| width | **int32_t** | Die Breite des Rechtecks, das die Ellipse definiert |
| height | **int32_t** | Die Höhe des Rechtecks, das die Ellipse definiert |
| startAngle | **int32_t** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum Startpunkt des Kuchenstücks |
| sweepAngle | **int32_t** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Kuchenstücks |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) Methode


Zeichnet das angegebene Kuchenstück mit dem angegebenen Stift auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Kuchenstücks verwendet wird |
| x | **float** | Die X-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| y | **float** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| width | **float** | Die Breite des Rechtecks, das die Ellipse definiert |
| height | **float** | Die Höhe des Rechtecks, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum Startpunkt des Kuchenstücks |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Kuchenstücks |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) Methode


Zeichnet das angegebene Kuchenstück mit dem angegebenen Stift auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Kuchenstücks verwendet wird |
| rect | [Rectangle](../../rectangle/) | Das Rechteck, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum Startpunkt des Kuchenstücks |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Kuchenstücks |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) Methode


Zeichnet das angegebene Kuchenstück mit dem angegebenen Stift auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Kuchenstücks verwendet wird |
| rect | [RectangleF](../../rectanglef/) | Das Rechteck, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum Startpunkt des Kuchenstücks |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Kuchenstücks |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Pen](../../pen/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [RectangleF](../../rectanglef/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)