---
title: FontsManager
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt den Schriftartenmanager zurück. Nur lesezugängliches IFontsManageraspose.slides/ifontsmanager.
type: docs
weight: 110
url: /de/aspose.slides/presentation/fontsmanager/
---

## Presentation.FontsManager-Eigenschaft

Gibt den Schriftartenmanager zurück. Nur lesezugänglich [`IFontsManager`](../../ifontsmanager).

```csharp
public IFontsManager FontsManager { get; }
```

### Beispiele

Das folgende Beispiel zeigt, wie man eingebettete Schriftarten in eine PowerPoint-Präsentation hinzufügt.

```csharp
[C#]
// Präsentation laden
using (Presentation presentation = new Presentation("Fonts.pptx"))
{
	// Quellschriftart laden, die ersetzt werden soll
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
	// Präsentation speichern
	presentation.Save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
}
```

### Siehe Auch

* Schnittstelle [IFontsManager](../../ifontsmanager)
* Klasse [Presentation](../../presentation)
* Namespace [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->