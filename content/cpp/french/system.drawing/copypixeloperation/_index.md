---
title: CopyPixelOperation
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie comment la couleur source dans une opération de copie de pixel est combinée avec la couleur de destination pour obtenir une couleur finale.
type: docs
weight: 391
url: /fr/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum


Spécifie comment la couleur source dans une opération de copie de pixel est combinée avec la couleur de destination pour produire une couleur finale.

```cpp
enum class CopyPixelOperation
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Le bitmap n’est pas mis en miroir. |
| Blackness | 66 | La région de destination est remplie en utilisant la couleur d'index 0 dans la palette physique. |
| NotSourceErase | 1114278 | Les couleurs source et destination sont combinées par OU et la couleur résultante est ensuite inversée. |
| NotSourceCopy | 3342344 | La région source est inversée puis copiée vers la destination. |
| SourceErase | 4457256 | Les couleurs inversées de la région de destination sont combinées par ET avec les couleurs de la région source. |
| DestinationInvert | 5570569 | La région de destination est inversée. |
| PatInvert | 5898313 | Les couleurs de la brosse actuellement sélectionnée dans le contexte de l'appareil de destination sont combinées par OU exclusif avec les couleurs de la destination. |
| SourceInvert | 6684742 | Les couleurs des régions source et destination sont combinées par OU exclusif. |
| SourceAnd | 8913094 | Les couleurs des régions source et destination sont combinées par ET. |
| MergePaint | 12255782 | Les couleurs de la région source inversée sont combinées par OU avec les couleurs de la région destination. |
| MergeCopy | 12583114 | Les couleurs de la région source sont combinées par ET avec les couleurs de la brosse sélectionnée du contexte de l'appareil de destination. |
| SourceCopy | 13369376 | La région source est copiée directement dans la région destination. |
| SourcePaint | 15597702 | Les couleurs des régions source et destination sont combinées par OU. |
| PatCopy | 15728673 | La brosse actuellement sélectionnée dans le contexte de l'appareil de destination est copiée vers le bitmap de destination. |
| PatPaint | 16452105 | Les couleurs de la brosse actuellement sélectionnée dans le contexte de l'appareil de destination sont combinées par OU avec les couleurs de la région source inversée. Le résultat de cette opération est combiné par OU avec les couleurs de la région destination. |
| Whiteness | 16711778 | La région de destination est remplie en utilisant la couleur d'index 1 dans la palette physique. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) qui sont superposés au-dessus de la fenêtre de l'application sont inclus dans l'image résultante. |

## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)