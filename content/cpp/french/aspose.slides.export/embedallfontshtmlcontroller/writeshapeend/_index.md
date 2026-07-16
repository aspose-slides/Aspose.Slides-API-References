---
title: WriteShapeEnd()
second_title: Référence API Aspose.Slides pour C++
description: Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive actuelle sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.
type: docs
weight: 79
url: /fr/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) méthode

Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le generator, la génération de l'image de la diapositive actuelle sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objet de sortie. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) qui est rendu en dernier. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [EmbedAllFontsHtmlController](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)