---
title: ApplyDefaultParagraphIndentsShifts
second_title: Aspose.Slides pour la référence API .NET
description: Définit des décalages par défaut non nuls pour les retraits de paragraphe efficaces et MarginLeft lorsque les puces sont activées, comme le fait PowerPoint si les puces/numérotations de paragraphe y sont activées. Si les puces sont désactivées, réinitialisez simplement le retrait de paragraphe et MarginLeft, comme le fait PowerPoint si les puces/numérotations de paragraphe y sont désactivées. Les décalages de retrait sont appliqués en fonction du contexte de puces actuel - IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Des décalages de retraits non nuls sont appliqués à l'Indent et MarginLeft efficaces du paragraphe actuel, rendant les valeurs résultantes locales.
type: docs
weight: 110
url: /fr/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---

## IBulletFormat.ApplyDefaultParagraphIndentsShifts méthode

Définit des décalages par défaut non nuls pour les retraits de paragraphe efficaces et MarginLeft lorsque les puces sont activées (comme le fait PowerPoint si les puces/numérotations de paragraphe y sont activées). Si les puces sont désactivées, réinitialisez simplement le retrait de paragraphe et MarginLeft (comme le fait PowerPoint si les puces/numérotations de paragraphe y sont désactivées). Les décalages de retrait sont appliqués en fonction du contexte de puces actuel - IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Des décalages de retraits non nuls sont appliqués à l'Indent et MarginLeft efficaces du paragraphe actuel (rendant les valeurs résultantes locales).

```csharp
public void ApplyDefaultParagraphIndentsShifts()
```

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Appeler cette méthode n'a pas d'importance et lance InvalidOperationException dans les cas suivants : si l'objet formaté parent n'est pas un paragraphe (par exemple, appeler ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() lancera une exception) ; ou si le paragraphe n'a pas été ajouté à une collection ITextFrame.Paragraphs (ajoutez-le d'abord) ; |

### Voir Aussi

* interface [IBulletFormat](../../ibulletformat)
* namespace [Aspose.Slides](../../ibulletformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->