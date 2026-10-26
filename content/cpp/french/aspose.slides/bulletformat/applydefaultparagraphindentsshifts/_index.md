---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit les décalages non nuls par défaut pour le Indent et le MarginLeft du paragraphe effectif lorsque les puces sont activées (comme PowerPoint le fait lorsqu’on active les puces/la numérotation de paragraphe). Si les puces sont désactivées, le Indent et le MarginLeft du paragraphe sont simplement réinitialisés (comme PowerPoint le fait lorsqu’on désactive les puces/la numérotation de paragraphe). Les décalages d’indentation sont appliqués en fonction du contexte de puce actuel - IBulletFormat::get(set)_Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d’indentation non nuls sont appliqués au Indent et au MarginLeft effectifs du paragraphe actuel (les valeurs résultantes deviennent des valeurs locales)."
type: docs
weight: 235
url: /fr/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() méthode

Définit les décalages non nuls par défaut pour le Indent et le MarginLeft du paragraphe effectif lorsque les puces sont activées (comme PowerPoint le fait lorsqu’on active les puces/la numérotation de paragraphe). Si les puces sont désactivées, les Indent et MarginLeft du paragraphe sont simplement réinitialisés (comme PowerPoint le fait lorsqu’on désactive les puces/la numérotation de paragraphe). Les décalages d’indentation sont appliqués en fonction du contexte de puce actuel - IBulletFormat::get(set)_Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d’indentation non nuls sont appliqués au Indent et au MarginLeft effectifs du paragraphe actuel (les valeurs résultantes deviennent des valeurs locales).

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```

## Voir aussi

* Classe [BulletFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)