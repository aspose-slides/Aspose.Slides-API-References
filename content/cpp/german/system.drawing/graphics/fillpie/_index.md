---
title: FillPie()
second_title: Aspose.Slides für C++ API-Referenz
description: Füllt das angegebene Kuchenstück mit dem angegebenen Pinsel auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.
type: docs
weight: 274
url: /de/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) Methode

Füllt das angegebene Kuchenstück mit dem angegebenen Pinsel auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein Pinsel, der beim Ausfüllen des Kuchenstücks verwendet wird |
| x | int | Die X-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| y | int | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| width | int | Die Breite des Rechtecks, das die Ellipse definiert |
| height | int | Die Höhe des Rechtecks, das die Ellipse definiert |
| startAngle | int | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum Startpunkt des Kuchenstücks |
| sweepAngle | int | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Kuchenstücks |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) Methode

Füllt das angegebene Kuchenstück mit dem angegebenen Pinsel auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein Pinsel, der beim Ausfüllen des Kuchenstücks verwendet wird |
| x | **float** | Die X-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| y | **float** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| width | **float** | Die Breite des Rechtecks, das die Ellipse definiert |
| height | **float** | Die Höhe des Rechtecks, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum Startpunkt des Kuchenstücks |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Kuchenstücks |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) Methode

Füllt das angegebene Kuchenstück mit dem angegebenen Pinsel auf der Oberfläche, die durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein Pinsel, der beim Ausfüllen des Kuchenstücks verwendet wird |
| rect | [Rectangle](../../rectangle/) | Das Rechteck, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum Startpunkt des Kuchenstücks |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Kuchenstücks |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Brush](../../brush/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)