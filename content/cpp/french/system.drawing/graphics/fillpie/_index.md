---
title: FillPie()
second_title: Référence API Aspose.Slides pour C++
description: Remplit la tarte spécifiée en utilisant le pinceau spécifié sur la surface représentée par l'objet actuel.
type: docs
weight: 274
url: /fr/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) méthode


Remplit la tarte spécifiée en utilisant le pinceau spécifié sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pinceau à utiliser lors du remplissage de la tarte |
| x | int | La coordonnée X du coin supérieur gauche du rectangle qui définit l'ellipse |
| y | int | La coordonnée Y du coin supérieur gauche du rectangle qui définit l'ellipse |
| width | int | La largeur du rectangle qui définit l'ellipse |
| height | int | La hauteur du rectangle qui définit l'ellipse |
| startAngle | int | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe X jusqu'au point de départ de la tarte |
| sweepAngle | int | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le **startAngle** jusqu'au point final de la tarte |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) méthode


Remplit la tarte spécifiée en utilisant le pinceau spécifié sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pinceau à utiliser lors du remplissage de la tarte |
| x | **float** | La coordonnée X du coin supérieur gauche du rectangle qui définit l'ellipse |
| y | **float** | La coordonnée Y du coin supérieur gauche du rectangle qui définit l'ellipse |
| width | **float** | La largeur du rectangle qui définit l'ellipse |
| height | **float** | La hauteur du rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe X jusqu'au point de départ de la tarte |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le **startAngle** jusqu'au point final de la tarte |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) méthode


Remplit la tarte spécifiée en utilisant le pinceau spécifié sur la surface représentée par l'objet actuel.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pinceau à utiliser lors du remplissage de la tarte |
| rect | [Rectangle](../../rectangle/) | Le rectangle qui définit l'ellipse |
| startAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis l'axe X jusqu'au point de départ de la tarte |
| sweepAngle | **float** | Angle en degrés mesuré dans le sens des aiguilles d'une montre depuis le **startAngle** jusqu'au point final de la tarte |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [Brush](../../brush/)
* classe [Graphics](../)
* classe [Rectangle](../../rectangle/)
* espace de noms [System::Drawing](../../)
* bibliothèque [Aspose.Slides](../../../)