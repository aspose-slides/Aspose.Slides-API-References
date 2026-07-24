---
title: DrawImageUnscaled()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeichnet das angegebene Bild in seiner ursprünglichen physischen Größe am angegebenen Ort.
type: docs
weight: 443
url: /de/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) Methode

Zeichnet das angegebene Bild in seiner ursprünglichen physischen Größe am angegebenen Ort.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | int | Die X-Koordinate der oberen linken Ecke des gezeichneten Bildes |
| y | int | Die Y-Koordinate der oberen linken Ecke des gezeichneten Bildes |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) Methode

Zeichnet ein angegebenes Bild in seiner ursprünglichen physischen Größe an einem angegebenen Ort.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| x | int | Die X-Koordinate der oberen linken Ecke des gezeichneten Bildes |
| y | int | Die Y-Koordinate der oberen linken Ecke des gezeichneten Bildes |
| width | int | Nicht verwendet |
| height | int | Nicht verwendet |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) Methode

Zeichnet ein angegebenes Bild in seiner ursprünglichen physischen Größe an einem angegebenen Ort.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| rect | const [Rectangle](../../rectangle/)\& | Das Rechteck, das die obere linke Ecke des gezeichneten Bildes angibt. Die X- und Y-Eigenschaften des Rechtecks geben die obere linke Ecke an. Die width- und height-Werte werden ignoriert. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) Methode

Zeichnet ein angegebenes Bild in seiner ursprünglichen physischen Größe an einem angegebenen Ort.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Das zu zeichnende Bild |
| point | const [Point](../../point/)\& | Die [Point](../../point/)-Struktur, die die obere linke Ecke des gezeichneten Bildes angibt. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../../image/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [Point](../../point/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)