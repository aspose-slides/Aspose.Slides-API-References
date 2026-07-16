---
title: SetSize()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit la taille de la diapositive par type et ajuste le contenu existant. Attribuer toute valeur différente de SlideSizeType::Custom ajuste le ISlideSize::get_Size en fonction du type sélectionné, tout en conservant ISlideSize::get_Orientation."
type: docs
weight: 53
url: /fr/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) méthode


Définit la taille de la diapositive par type et ajuste le contenu existant. Attribuer toute valeur différente de [SlideSizeType::Custom](../../slidesizetype/) ajuste le [ISlideSize::get_Size](../get_size/) en fonction du type sélectionné, tout en conservant [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | La taille de diapositive prédéfinie à appliquer. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Le mode de mise à l’échelle du contenu à utiliser. |
## Remarques


Attribuer toute valeur différente de [SlideSizeType::Custom](../../slidesizetype/) ajuste le [System::Drawing::Size](../../../system.drawing/size/) en fonction du type sélectionné, tout en conservant [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) méthode


Définit explicitement les dimensions de la diapositive et ajuste le contenu existant. Cela réinitialise la valeur [ISlideSize::get_Type](../get_type/) à [SlideSizeType::Custom](../../slidesizetype/) et définit le [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| width | **float** | La nouvelle largeur de la diapositive, en points. |
| height | **float** | La nouvelle hauteur de la diapositive, en points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Le mode de mise à l’échelle du contenu à utiliser. |
## Remarques


Cela réinitialise la propriété [ISlideSize::get_Type](../get_type/) à [SlideSizeType::Custom](../../slidesizetype/) et définit le [Orientation](../../orientation/). 

## Voir aussi

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)