---
title: IFontsManager class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ifontsmanager/
---
## IFontsManager klasse

Beheert lettertypen in de presentatie.

Het IFontsManager-type biedt de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/nl/aspose.slides/ifontsmanager/font_subst_rule_list/) | Lettertypevervangingen die gebruikt worden bij het renderen<br/>            Lezen/Schrijven [`IFontSubstRuleCollection`](/slides/python-net/nl/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/nl/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Stelt een gebruikersverzameling van FontFallBack-regels voor voor het beheren van collecties van lettertypen voor juiste vervangingen via fallback-functionaliteit<br/>            Lezen/Schrijven [`IFontFallBackRulesCollection`](/slides/python-net/nl/aspose.slides/ifontfallbackrulescollection). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_substitutions/#) | Haalt de informatie op over lettertypen die bij het renderen van de presentatie worden vervangen. |
| [`get_substitutions(self, slides)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_substitutions/#listint) | Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia's worden vervangen. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Voegt het ingesloten lettertype toe.<br/>            Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het kopiëren. Zoek eerst de licentie van <br/>            een lettertype op en controleer of het vrij kan worden overgedragen naar een andere machine. Een ArgumentException kan worden gegooid als lettertypegegevens None zijn of dit lettertype al is ingesloten |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Voegt het ingesloten lettertype toe<br/>            Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het toevoegen. Zoek eerst de licentie van <br/>            een lettertype op en controleer of het vrij kan worden overgedragen naar een andere machine. Een ArgumentException kan worden gegooid als lettertypegegevens None zijn of dit lettertype al is ingesloten |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/nl/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Vervang lettertype in presentatie |
| [`replace_font(self, subst_rule)`](/slides/python-net/nl/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Vervang lettertype in presentatie met behulp van informatie verstrekt in [`IFontSubstRule`](/slides/python-net/nl/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/nl/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Vervang lettertype in presentatie met behulp van informatie verstrekt in collectie van [`IFontSubstRule`](/slides/python-net/nl/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_fonts/#) | Retourneert de lettertypen die in de presentatie worden gebruikt |
| [`get_embedded_fonts(self)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Retourneert de ingesloten lettertypen in de presentatie |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/nl/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Verwijdert het ingesloten lettertype |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Haalt de byte-array op die de lettertypegegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertypegegevens. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)