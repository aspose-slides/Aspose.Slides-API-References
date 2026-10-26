---
title: DrawArc()
second_title: Référence de l'API Aspose.Slides pour C++
description: Dessine l'arc spécifié à l'aide du stylo indiqué sur la surface représentée par l'objet actuel.
type: docs
weight: 248
url: /fr/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) méthode


Dessine l'arc spécifié à l'aide du stylo indiqué sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un stylo à utiliser pour tracer l'arc |
| x | **int32_t** | La coordonnée X du coin supérieur gauche du rectangle qui définit l'ellipse |
| y | **int32_t** | La coordonnée Y du coin supérieur gauche du rectangle qui définit l'ellipse |
| width | **int32_t** | La largeur du rectangle qui définit l'ellipse |
| height | **int32_t** | La hauteur du rectangle qui définit l'ellipse |
| startAngle | **int32_t** | Angle en degrés mesuré dans le sens horaire depuis l'axe X jusqu'au point de départ de l'arc |
| sweepAngle | **int32_t** | Angle en degrés mesuré dans le sens horaire depuis le **startAngle** jusqu'au point final de l'arc |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) méthode


Dessine l'arc spécifié à l'aide du stylo indiqué sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un stylo à utiliser pour tracer l'arc |
| x | **float** | La coordonnée X du coin supérieur gauche du rectangle qui définit l'ellipse |
| y | **float** | La coordonnée Y du coin supérieur gauche du rectangle qui définit l'ellipse |
| width | **float** | La largeur du rectangle qui définit l'ellipse |
| height | **float** | La hauteur du rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens horaire depuis l'axe X jusqu'au point de départ de l'arc |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens horaire depuis le **startAngle** jusqu'au point final de l'arc |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) méthode


Dessine l'arc spécifié à l'aide du stylo indiqué sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un stylo à utiliser pour tracer l'arc |
| rect | [Rectangle](../../rectangle/) | Le rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens horaire depuis l'axe X jusqu'au point de départ de l'arc |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens horaire depuis le **startAngle** jusqu'au point final de l'arc |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) méthode


Dessine l'arc spécifié à l'aide du stylo indiqué sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un stylo à utiliser pour tracer l'arc |
| rect | [RectangleF](../../rectanglef/) | Le rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens horaire depuis l'axe X jusqu'au point de départ de l'arc |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens horaire depuis le **startAngle** jusqu'au point final de l'arc |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)