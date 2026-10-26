---
title: WriteShapeStart()
second_title: Référence API Aspose.Slides pour C++
description: Appelée avant le rendu de la forme. Appelée une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.
type: docs
weight: 66
url: /fr/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) méthode


Appelée avant le rendu de la forme. Appelée une fois par chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté inséré et une nouvelle image sera démarrée au-dessus de la précédente.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objet de sortie. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) qui est sur le point d'être rendu. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IHtmlGenerator](../../ihtmlgenerator/)
* classe [IShape](../../../aspose.slides/ishape/)
* classe [EmbedAllFontsHtmlController](../)
* espace de noms [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)