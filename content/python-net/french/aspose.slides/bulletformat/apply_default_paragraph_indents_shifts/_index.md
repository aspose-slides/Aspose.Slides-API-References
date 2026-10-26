---
title: apply_default_paragraph_indents_shifts method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Définit les décalages non nuls par défaut pour le Indent et le MarginLeft effectifs du paragraphe lorsque les puces sont activées (comme PowerPoint le fait si l’on active les puces/la numérotation de paragraphe). Si les puces sont désactivées, réinitialise simplement le Indent et le MarginLeft du paragraphe (comme PowerPoint le fait si l’on désactive les puces/la numérotation de paragraphe). Les décalages d’indentation sont appliqués en fonction du contexte de puce actuel – IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d’indentation non nuls sont appliqués au Indent et au MarginLeft effectifs du paragraphe actuel (pour que les valeurs résultantes soient locales).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | L'appel de cette méthode n'a pas d'importance et déclenche **System.InvalidOperationException** dans les cas suivants :<br/>            si l'objet formaté parent n'est pas un paragraphe (par exemple appeler ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() déclenchera une exception) ;<br/>            ou si le paragraphe n'a pas été ajouté à aucune collection ITextFrame.Paragraphs (ajoutez-le d'abord) ; |



### Voir aussi
* classe [`BulletFormat`](/slides/python-net/fr/aspose.slides/bulletformat)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)