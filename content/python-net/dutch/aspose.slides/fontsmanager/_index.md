---
title: FontsManager class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/fontsmanager/
---
## FontsManager klasse

Beheert lettertypen in de gehele presentatie.

Het FontsManager-type geeft de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/nl/aspose.slides/fontsmanager/font_subst_rule_list/) | Lettertypevervangingen te gebruiken bij het renderen.<br/>            Lezen/Schrijven [`IFontSubstRuleCollection`](/slides/python-net/nl/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/nl/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Stelt de collectie van een gebruiker met FontFallBack-regels voor voor het beheren van collecties van lettertypen voor juiste vervangingen via fallback-functionaliteit<br/>            Lezen/Schrijven [`IFontFallBackRulesCollection`](/slides/python-net/nl/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/nl/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Specificeert of geregistreerde lettertypen de voorkeur moeten krijgen boven ingesloten lettertypen met dezelfde naam en stijl.<br/>            Indien ingeschakeld, worden overeenkomende ingesloten lettertypen tijdelijk vervangen door de overeenkomende geregistreerde lettertypen tijdens export. |

## Methoden

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_substitutions/#) | Haalt de informatie op over lettertypen die bij het renderen van de presentatie zullen worden vervangen. |
| [`get_substitutions(self, slides)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_substitutions/#listint) | Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia's zullen worden vervangen. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Voegt het ingesloten lettertype toe<br/>            Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het kopiëren. Zoek eerst de licentie van <br/>            een lettertype op en controleer of deze vrij kan worden overgedragen naar een andere machine. Een ArgumentException kan worden gegooid als font data None is of dit lettertype al is ingesloten |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Voegt het ingesloten lettertype toe<br/>            Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het kopiëren. Zoek eerst de licentie van <br/>            een lettertype op en controleer of deze vrij kan worden overgedragen naar een andere machine. Een ArgumentException kan worden gegooid als font data None is of dit lettertype al is ingesloten |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/nl/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Vervang lettertype in de presentatie |
| [`replace_font(self, subst_rule)`](/slides/python-net/nl/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Vervang lettertype in de presentatie met behulp van de informatie die is verstrekt in [`FontSubstRule`](/slides/python-net/nl/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/nl/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Vervang lettertype in de presentatie met behulp van de informatie die is verstrekt in een collectie van [`FontSubstRule`](/slides/python-net/nl/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_fonts/#) | Retourneert de lettertypen die in de presentatie worden gebruikt |
| [`get_embedded_fonts(self)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_embedded_fonts/#) | Retourneert de ingesloten lettertypen in de presentatie |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/nl/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Verwijdert het ingesloten lettertype |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Haalt de byte-array op die de lettertype-gegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertype-gegevens. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Bepaalt het inbedniveau van een lettertype op basis van de gegeven byte-array en lettertype naam. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)