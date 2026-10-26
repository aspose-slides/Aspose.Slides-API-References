---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Définit les décalages non nuls par défaut pour l'Indent et le MarginLeft du paragraphe effectif lorsque les puces sont activées (comme PowerPoint le fait si l’on active les puces/numérotation des paragraphes). Si les puces sont désactivées, réinitialise simplement l'Indent et le MarginLeft du paragraphe (comme PowerPoint le fait si l’on désactive les puces/numérotation des paragraphes). Les décalages d'indentation sont appliqués en fonction du contexte de puce actuel – IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'Indent et au MarginLeft effectifs du paragraphe actuel (les valeurs résultantes deviennent des valeurs locales).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Appeler cette méthode n'a aucune importance et génère **System.InvalidOperationException** dans les cas suivants :<br/>            si l'objet formaté parent n'est pas un paragraphe (par exemple appeler ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() lancera une exception) ;<br/>            ou si le paragraphe n'a pas été ajouté à la collection ITextFrame.Paragraphs (ajoutez-le d'abord) ; |

### Voir aussi
* classe [`IBulletFormat`](/slides/python-net/fr/aspose.slides/ibulletformat)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)