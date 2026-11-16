---
title: FontsManager
second_title: Aspose.Sildes für .NET API-Referenz
description: Verwaltet Schriftarten in der gesamten Präsentation.
type: docs
weight: 4960
url: /de/aspose.slides/fontsmanager/
---
## FontsManager Klasse

Verwaltet Schriftarten in der gesamten Präsentation.

```csharp
public class FontsManager : IFontsManager
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/fontsmanager/fontfallbackrulescollection) { get; set; } | Stellt die Sammlung von FontFallBack-Regeln eines Benutzers für die Verwaltung von Schriftarten-Sammlungen für korrekte Ersetzungen durch Fallback-Funktionalität dar. Lese/Schreiben [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/fontsmanager/fontsubstrulelist) { get; set; } | Schriftarten-Ersetzungen, die beim Rendern verwendet werden. Lese/Schreiben [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |
| [PreferRegisteredFontsOverEmbedded](../../aspose.slides/fontsmanager/preferregisteredfontsoverembedded) { get; set; } | Gibt an, ob registrierte Schriftarten gegenüber eingebetteten Schriftarten mit gleichem Namen und Stil bevorzugt werden sollen. Wenn aktiviert, werden passende eingebettete Schriftarten während des Exports vorübergehend durch die entsprechenden registrierten Schriftarten ersetzt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Fügt die eingebettete Schriftart hinzu. Beachten Sie beim Kopieren von Schriftarten, dass die meisten Schriftarten urheberrechtlich geschützt sind. Ermitteln Sie zuerst die Lizenz einer Schriftart und prüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten null sind oder diese Schriftart bereits eingebettet ist. |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Fügt die eingebettete Schriftart hinzu. Beachten Sie beim Kopieren von Schriftarten, dass die meisten Schriftarten urheberrechtlich geschützt sind. Ermitteln Sie zuerst die Lizenz einer Schriftart und prüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten null sind oder diese Schriftart bereits eingebettet ist. |
| [GetEmbeddedFonts](../../aspose.slides/fontsmanager/getembeddedfonts)() | Gibt die in der Präsentation eingebetteten Schriftarten zurück. |
| [GetFontBytes](../../aspose.slides/fontsmanager/getfontbytes)(IFontData, FontStyleType) | Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftartdaten darstellt. |
| [GetFontEmbeddingLevel](../../aspose.slides/fontsmanager/getfontembeddinglevel)(byte[], string) | Bestimmt das Einbettungslevel einer Schriftart anhand des angegebenen Byte-Arrays und des Schriftartnamens. |
| [GetFonts](../../aspose.slides/fontsmanager/getfonts)() | Gibt die in der Präsentation verwendeten Schriftarten zurück. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions)() | Ermittelt die Informationen über Schriftarten, die bei der Darstellung der Präsentation ersetzt werden. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions_1)(int[]) | Ermittelt die Informationen über Schriftarten, die während der Darstellung der angegebenen Folien ersetzt werden. |
| [RemoveEmbeddedFont](../../aspose.slides/fontsmanager/removeembeddedfont)(IFontData) | Entfernt die eingebettete Schriftart. |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Ersetzt die Schriftart in der Präsentation mithilfe der in [`FontSubstRule`](../fontsubstrule) bereitgestellten Informationen. |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Ersetzt die Schriftart in der Präsentation mithilfe der in der Sammlung von [`FontSubstRule`](../fontsubstrule) bereitgestellten Informationen. |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont)(IFontData, IFontData) | Ersetzt die Schriftart in der Präsentation. |

### Beispiele

Das folgende Beispiel zeigt, wie eingebettete Schriftarten zu einer PowerPoint-Präsentation hinzugefügt werden.

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

### Siehe auch

* Schnittstelle [IFontsManager](../ifontsmanager)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->