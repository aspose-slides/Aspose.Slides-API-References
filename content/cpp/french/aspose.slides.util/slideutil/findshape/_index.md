---
title: FindShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: Trouve la forme par texte alternatif dans une présentation PPTX.
type: docs
weight: 1
url: /fr/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) méthode

Trouve la forme par texte alternatif dans une présentation PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Présentation analysée. |
| altText | [System::String](../../../system/string/) | Texte alternatif d'une forme. |

### Valeur de retour

[Shape](../../../aspose.slides/shape/) ou null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) méthode

Recherche une forme par texte alternatif sur une diapositive dans une présentation PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Diapositive analysée. |
| altText | [System::String](../../../system/string/) | Texte alternatif d'une forme. |

### Valeur de retour

[Shape](../../../aspose.slides/shape/) ou null.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [String](../../../system/string/)
* Classe [SlideUtil](../)
* Classe [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Espace de noms [Aspose::Slides::Util](../../)
* Bibliothèque [Aspose.Slides](../../../)