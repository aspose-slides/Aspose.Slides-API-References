---
title: DrawArc()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeichnet den angegebenen Bogen mit dem angegebenen Stift auf der Oberfläche, die vom aktuellen Objekt repräsentiert wird.
type: docs
weight: 248
url: /de/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) Methode

Zeichnet den angegebenen Bogen mit dem angegebenen pen auf der Oberfläche, die vom aktuellen Objekt repräsentiert wird.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein pen, der beim Zeichnen des Bogens verwendet wird |
| x | **int32_t** | Die X-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| y | **int32_t** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| width | **int32_t** | Die width des Rechtecks, das die Ellipse definiert |
| height | **int32_t** | Die height des Rechtecks, das die Ellipse definiert |
| startAngle | **int32_t** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum **startAngle** |
| sweepAngle | **int32_t** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Bogens |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) Methode

Zeichnet den angegebenen Bogen mit dem angegebenen pen auf der Oberfläche, die vom aktuellen Objekt repräsentiert wird.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein pen, der beim Zeichnen des Bogens verwendet wird |
| x | **float** | Die X-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| y | **float** | Die Y-Koordinate der oberen linken Ecke des Rechtecks, das die Ellipse definiert |
| width | **float** | Die width des Rechtecks, das die Ellipse definiert |
| height | **float** | Die height des Rechtecks, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum **startAngle** |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Bogens |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) Methode

Zeichnet den angegebenen Bogen mit dem angegebenen pen auf der Oberfläche, die vom aktuellen Objekt repräsentiert wird.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein pen, der beim Zeichnen des Bogens verwendet wird |
| rect | [Rectangle](../../rectangle/) | Das Rechteck, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum **startAngle** |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Bogens |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) Methode

Zeichnet den angegebenen Bogen mit dem angegebenen pen auf der Oberfläche, die vom aktuellen Objekt repräsentiert wird.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein pen, der beim Zeichnen des Bogens verwendet wird |
| rect | [RectangleF](../../rectanglef/) | Das Rechteck, das die Ellipse definiert |
| startAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn von der X-Achse zum **startAngle** |
| sweepAngle | **float** | Winkel in Grad, gemessen im Uhrzeigersinn vom **startAngle** zum Endpunkt des Bogens |

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)