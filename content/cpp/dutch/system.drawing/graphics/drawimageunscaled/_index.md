---
title: DrawImageUnscaled()
second_title: Aspose.Slides voor C++ API-referentie
description: Tekent de opgegeven afbeelding met zijn originele fysieke grootte op de opgegeven locatie.
type: docs
weight: 443
url: /nl/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) methode

Tekent de opgegeven afbeelding met zijn originele fysieke grootte op de opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding om te tekenen |
| x | int | De X-coördinaat van de linkerbovenhoek van de getekende afbeelding |
| y | int | De Y-coördinaat van de linkerbovenhoek van de getekende afbeelding |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) methode

Tekent een opgegeven afbeelding met zijn originele fysieke grootte op een opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding om te tekenen |
| x | int | De X-coördinaat van de linkerbovenhoek van de getekende afbeelding |
| y | int | De Y-coördinaat van de linkerbovenhoek van de getekende afbeelding |
| width | int | Niet gebruikt |
| height | int | Niet gebruikt |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) methode

Tekent een opgegeven afbeelding met zijn originele fysieke grootte op een opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding om te tekenen |
| rect | const [Rectangle](../../rectangle/)\& | De rechthoek die de linkerbovenhoek van de getekende afbeelding specificeert. De X- en Y-eigenschappen van de rechthoek bepalen de linkerbovenhoek. De breedte- en hoogtewaarden worden genegeerd. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) methode

Tekent een opgegeven afbeelding met zijn originele fysieke grootte op een opgegeven locatie.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De afbeelding om te tekenen |
| point | const [Point](../../point/)\& | De [Point](../../point/) structuur die de linkerbovenhoek van de getekende afbeelding specificeert. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../../image/)
* Klasse [Graphics](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [Point](../../point/)
* Namespace [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)