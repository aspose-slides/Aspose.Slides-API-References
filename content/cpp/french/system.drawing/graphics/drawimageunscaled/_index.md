---
title: DrawImageUnscaled()
second_title: Référence de l'API Aspose.Slides pour C++
description: Dessine l'image spécifiée en utilisant sa taille physique originale à l'emplacement indiqué.
type: docs
weight: 443
url: /fr/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) méthode

Dessine l'image spécifiée en utilisant sa taille physique originale à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | int | La coordonnée X du coin supérieur gauche de l'image dessinée |
| y | int | La coordonnée Y du coin supérieur gauche de l'image dessinée |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) méthode

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | int | La coordonnée X du coin supérieur gauche de l'image dessinée |
| y | int | La coordonnée Y du coin supérieur gauche de l'image dessinée |
| width | int | Non utilisé |
| height | int | Non utilisé |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) méthode

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| rect | const [Rectangle](../../rectangle/)\& | Le rectangle qui spécifie le coin supérieur gauche de l'image dessinée. Les propriétés X et Y du rectangle spécifient le coin supérieur gauche. Les valeurs de largeur et de hauteur sont ignorées. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) méthode

Dessine une image spécifiée en utilisant sa taille physique originale à un emplacement spécifié.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| point | const [Point](../../point/)\& | La structure [Point](../../point/) qui spécifie le coin supérieur gauche de l'image dessinée. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../../image/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [Point](../../point/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)