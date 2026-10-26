---
title: DrawRectangle()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeichnet das angegebene Rechteck mit dem angegebenen Stift auf der Oberfläche, die das aktuelle Objekt darstellt.
type: docs
weight: 287
url: /de/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) Methode

Zeichnet das angegebene Rechteck mit dem angegebenen Stift auf der Oberfläche, die das aktuelle Objekt darstellt.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Rechtecks verwendet wird |
| x | int | Die X-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks |
| y | int | Die Y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks |
| width | int | Die Breite des zu zeichnenden Rechtecks |
| height | int | Die Höhe des zu zeichnenden Rechtecks |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) Methode

Zeichnet das angegebene Rechteck mit dem angegebenen Stift auf der Oberfläche, die das aktuelle Objekt darstellt.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Rechtecks verwendet wird |
| x | **float** | Die X-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks |
| y | **float** | Die Y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks |
| width | **float** | Die Breite des zu zeichnenden Rechtecks |
| height | **float** | Die Höhe des zu zeichnenden Rechtecks |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) Methode

Zeichnet das angegebene Rechteck mit dem angegebenen Stift auf der Oberfläche, die das aktuelle Objekt darstellt.

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Rechtecks verwendet wird |
| rect | [Rectangle](../../rectangle/) | Ein [Rectangle](../../rectangle/)-Objekt, das die Position und Größe des zu zeichnenden Rechtecks angibt |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)