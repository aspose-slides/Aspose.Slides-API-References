---
title: DrawPie()
second_title: Référence de l'API Aspose.Slides pour C++
description: Dessine le camembert spécifié en utilisant le crayon spécifié sur la surface représentée par l'objet actuel.
type: docs
weight: 261
url: /fr/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) method

Dessine le camembert spécifié en utilisant le crayon spécifié sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un crayon à utiliser lors du dessin du camembert |
| x | **int32_t** | La coordonnée X du coin supérieur gauche du rectangle qui définit l'ellipse |
| y | **int32_t** | La coordonnée Y du coin supérieur gauche du rectangle qui définit l'ellipse |
| width | **int32_t** | La largeur du rectangle qui définit l'ellipse |
| height | **int32_t** | La hauteur du rectangle qui définit l'ellipse |
| startAngle | **int32_t** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe X jusqu'au point de départ du camembert |
| sweepAngle | **int32_t** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le **startAngle** jusqu'au point final du camembert |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) method

Dessine le camembert spécifié en utilisant le crayon spécifié sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un crayon à utiliser lors du dessin du camembert |
| x | **float** | La coordonnée X du coin supérieur gauche du rectangle qui définit l'ellipse |
| y | **float** | La coordonnée Y du coin supérieur gauche du rectangle qui définit l'ellipse |
| width | **float** | La largeur du rectangle qui définit l'ellipse |
| height | **float** | La hauteur du rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe X jusqu'au point de départ du camembert |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le **startAngle** jusqu'au point final du camembert |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) method

Dessine le camembert spécifié en utilisant le crayon spécifié sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un crayon à utiliser lors du dessin du camembert |
| rect | [Rectangle](../../rectangle/) | Le rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe X jusqu'au point de départ du camembert |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le **startAngle** jusqu'au point final du camembert |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) method

Dessine le camembert spécifié en utilisant le crayon spécifié sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un crayon à utiliser lors du dessin du camembert |
| rect | [RectangleF](../../rectanglef/) | Le rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe X jusqu'au point de départ du camembert |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le **startAngle** jusqu'au point final du camembert |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)