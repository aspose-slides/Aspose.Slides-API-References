---
title: GetAllTextFrames()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie toutes les zones de texte d'une présentation PPTX.
type: docs
weight: 79
url: /fr/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) method

Renvoie toutes les zones de texte d’une présentation PPTX.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Présentation analysée. |
| withMasters | **bool** | Détermine si les diapositives maîtres doivent être analysées. |

### Valeur de retour

Tableau d’objets [TextFrame](../../../aspose.slides/textframe/).

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [SlideUtil](../)
* Espace de noms [Aspose::Slides::Util](../../)
* Bibliothèque [Aspose.Slides](../../../)