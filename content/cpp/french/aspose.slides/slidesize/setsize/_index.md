---
title: SetSize()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la taille de la diapositive par type et redimensionne le contenu existant.
type: docs
weight: 53
url: /fr/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) méthode

Définit la taille de la diapositive par type et redimensionne le contenu existant.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |

## Remarques

Attribuer une valeur différente de [SlideSizeType::Custom](../../slidesizetype/) ajuste le [SlideSize::get_Size](../get_size/) en fonction du type sélectionné, tout en conservant [SlideSize::get_Orientation](../get_orientation/).

## SlideSize::SetSize(float, float, SlideSizeScaleType) méthode

Définit explicitement les dimensions de la diapositive et redimensionne le contenu existant.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| width | **float** | La nouvelle largeur de la diapositive, en points. |
| height | **float** | La nouvelle hauteur de la diapositive, en points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Le mode de mise à l'échelle du contenu à utiliser. |

## Remarques

Cela réinitialise la propriété [SlideSize::get_Type](../get_type/) à [SlideSizeType::Custom](../../slidesizetype/) et définit le [Orientation](../../orientation/).

## Voir aussi

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [SlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)