---
title: WriteShapeStart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.
type: docs
weight: 53
url: /fr/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) méthode

Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objet de sortie. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) qui est sur le point d'être rendu. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IHtmlFormattingController](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)