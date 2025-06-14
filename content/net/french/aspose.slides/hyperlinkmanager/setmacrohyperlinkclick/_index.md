---
title: SetMacroHyperlinkClick
second_title: Référence API Aspose.Slides pour .NET
description: Définir un lien hypertexte de macro au clic.
type: docs
weight: 70
url: /fr/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---

## HyperlinkManager.SetMacroHyperlinkClick méthode

Définir un lien hypertexte de macro au clic.

```csharp
public IHyperlink SetMacroHyperlinkClick(string macroName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| macroName | String | Nom de la macro |

### Valeur de retour

Objet Hyperlink [`IHyperlink`](../../ihyperlink)

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation())
{
    IAutoShape shape = presentation.Slides[0].Shapes.AddAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
    shape.HyperlinkManager.SetMacroHyperlinkClick("MacroName");
}
```

### Voir aussi

* interface [IHyperlink](../../ihyperlink)
* classe [HyperlinkManager](../../hyperlinkmanager)
* espace de noms [Aspose.Slides](../../hyperlinkmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->