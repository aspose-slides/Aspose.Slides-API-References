---
title: FontsManager
second_title: Aspose.Sildes voor .NET API-referentie
description: Beheert lettertypen in de presentatie.
type: docs
weight: 4960
url: /nl/aspose.slides/fontsmanager/
---
## FontsManager klasse

Beheert lettertypen in de volledige presentatie.

```csharp
public class FontsManager : IFontsManager
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/fontsmanager/fontfallbackrulescollection) { get; set; } | Stelt een verzameling van FontFallBack-regels van een gebruiker voor voor het beheren van collecties van lettertypen voor correcte substituties via fallback-functionaliteit Lezen/schrijven [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/fontsmanager/fontsubstrulelist) { get; set; } | Lettertypevervangingen om te gebruiken bij het renderen. Lezen/schrijven [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |
| [PreferRegisteredFontsOverEmbedded](../../aspose.slides/fontsmanager/preferregisteredfontsoverembedded) { get; set; } | Specificeert of geregistreerde lettertypen de voorkeur moeten krijgen boven ingesloten lettertypen met dezelfde lettertype-naam en stijl. Indien ingeschakeld, worden overeenkomende ingesloten lettertypen tijdelijk vervangen door de corresponderende geregistreerde lettertypen tijdens export. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Voegt het ingesloten lettertype toe. Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het kopiëren. Zoek eerst de licentie van een lettertype op en controleer of het vrij kan worden overgedragen naar een andere machine. Er kan een ArgumentException worden gegooid als lettertype-gegevens null zijn of het lettertype al is ingesloten. |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Voegt het ingesloten lettertype toe. Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het kopiëren. Zoek eerst de licentie van een lettertype op en controleer of het vrij kan worden overgedragen naar een andere machine. Er kan een ArgumentException worden gegooid als lettertype-gegevens null zijn of het lettertype al is ingesloten. |
| [GetEmbeddedFonts](../../aspose.slides/fontsmanager/getembeddedfonts)() | Geeft de ingesloten lettertypen in de presentatie terug |
| [GetFontBytes](../../aspose.slides/fontsmanager/getfontbytes)(IFontData, FontStyleType) | Haalt de byte-array op die de lettertype-gegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertype-gegevens. |
| [GetFontEmbeddingLevel](../../aspose.slides/fontsmanager/getfontembeddinglevel)(byte[], string) | Bepaalt het insluitingsniveau van een lettertype op basis van de opgegeven byte-array en lettertype-naam. |
| [GetFonts](../../aspose.slides/fontsmanager/getfonts)() | Geeft de in de presentatie gebruikte lettertypen terug |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions)() | Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie worden vervangen. |
| [GetSubstitutions](../../aspose.slides/fontsmanager/getsubstitutions#getsubstitutions_1)(int[]) | Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia's worden vervangen. |
| [RemoveEmbeddedFont](../../aspose.slides/fontsmanager/removeembeddedfont)(IFontData) | Verwijdert het ingesloten lettertype |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Vervangt het lettertype in de presentatie met behulp van de informatie die is opgegeven in [`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Vervangt het lettertype in de presentatie met behulp van de informatie die is opgegeven in de verzameling van [`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont)(IFontData, IFontData) | Vervangt het lettertype in de presentatie |

### Voorbeelden

Het volgende voorbeeld toont hoe ingesloten lettertypen aan een PowerPoint-presentatie kunnen worden toegevoegd.

```csharp
[C#]
// Laad presentatie
using (Presentation presentation = new Presentation("Fonts.pptx"))
{
	// Laad bronlettertype om te vervangen
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
	// Sla de presentatie op
	presentation.Save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IFontsManager](../ifontsmanager)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->