---
title: FontsManager class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/fontsmanager/
---
## FontsManager klasse

Beheert lettertypen in de presentatie.

Het FontsManager-type geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/nl/aspose.slides/fontsmanager/font_subst_rule_list/) | Lettertypevervangingen om te gebruiken bij het renderen.<br/>            Lezen/schrijven [`IFontSubstRuleCollection`](/slides/python-net/nl/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/nl/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Vertegenwoordigt een verzameling FontFallBack-regels van een gebruiker voor het beheren van collecties van lettertypen voor juiste vervangingen door fallback-functionaliteit<br/>            Lezen/schrijven [`IFontFallBackRulesCollection`](/slides/python-net/nl/aspose.slides/ifontfallbackrulescollection). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_substitutions/#) | Haalt de informatie over lettertypen op die tijdens het renderen van de presentatie worden vervangen. |
| [`get_substitutions(self, slides)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_substitutions/#listint) | Haalt de informatie over lettertypen op die tijdens het renderen van de opgegeven dia's worden vervangen. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Voegt het ingesloten lettertype toe<br/>            Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het kopiëren. Zoek eerst de licentie van <br/>            een lettertype op en controleer of deze vrij kan worden overgedragen naar een andere machine. Een ArgumentException kan worden gegooid als font data None is of dit lettertype al is ingesloten |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Voegt het ingesloten lettertype toe<br/>            Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn bij het kopiëren. Zoek eerst de licentie van <br/>            een lettertype op en controleer of deze vrij kan worden overgedragen naar een andere machine. Een ArgumentException kan worden gegooid als font data None is of dit lettertype al is ingesloten |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/nl/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Vervang lettertype in de presentatie |
| [`replace_font(self, subst_rule)`](/slides/python-net/nl/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Vervang lettertype in de presentatie met behulp van de informatie verstrekt in [`FontSubstRule`](/slides/python-net/nl/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/nl/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Vervang lettertype in de presentatie met behulp van de informatie verstrekt in de verzameling van [`FontSubstRule`](/slides/python-net/nl/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_fonts/#) | Retourneert de lettertypen die in de presentatie worden gebruikt |
| [`get_embedded_fonts(self)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_embedded_fonts/#) | Retourneert de in de presentatie ingesloten lettertypen |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/nl/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Verwijdert het ingesloten lettertype |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Haalt de byte-array op die de lettertypegegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertypegegevens. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/nl/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Bepaalt het insluitniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)