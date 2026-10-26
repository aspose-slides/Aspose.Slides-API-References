---
title: FormatText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cette fonction est appelée avant le rendu de la portion de texte en SVG afin de permettre à l'utilisateur de contrôler le SVG résultant.
type: docs
weight: 1
url: /fr/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) méthode


Cette fonction est appelée avant le rendu de la portion de texte en SVG afin de permettre à l'utilisateur de contrôler le SVG résultant.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Objet permettant de contrôler la génération du tspan SVG. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Portion source. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Cadre de texte de la portion source. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISvgTSpan](../../isvgtspan/)
* Classe [IPortion](../../../aspose.slides/iportion/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [ISvgShapeAndTextFormattingController](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)