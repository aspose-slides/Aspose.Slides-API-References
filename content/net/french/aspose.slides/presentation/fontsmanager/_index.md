---
title: FontsManager
second_title: Aspose.Sildes pour .NET API Référence
description: Renvoie le gestionnaire de polices. IFontsManager en lecture seule aspose.slides/ifontsmanager.
type: docs
weight: 110
url: /fr/aspose.slides/presentation/fontsmanager/
---

## Propriété Presentation.FontsManager

Renvoie le gestionnaire de polices. Lecture seule [`IFontsManager`](../../ifontsmanager).

```csharp
public IFontsManager FontsManager { get; }
```

### Exemples

L'exemple suivant montre comment ajouter des polices intégrées à la présentation PowerPoint.

```csharp
[C#]
// Charger la présentation
using (Presentation presentation = new Presentation("Fonts.pptx"))
{
	// Charger la police source à remplacer
	IFontData sourceFont = new FontData("Arial");
	IFontData[] allFonts = presentation.FontsManager.GetFonts();
	IFontData[] embeddedFonts = presentation.FontsManager.GetEmbeddedFonts();
	foreach (IFontData font in allFonts)
	{
		if (!embeddedFonts.Contains(font))
		{
			presentation.FontsManager.AddEmbeddedFont(font, EmbedFontCharacters.All);
		}
	}
	// Sauvegarder la présentation
	presentation.Save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
}
```

### Voir Aussi

* interface [IFontsManager](../../ifontsmanager)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->