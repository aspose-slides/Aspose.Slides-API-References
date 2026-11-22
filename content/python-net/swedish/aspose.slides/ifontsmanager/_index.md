---
title: IFontsManager class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ifontsmanager/
---
## IFontsManager klass

Hantera typsnitt över hela presentationen.

IFontsManager-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/sv/aspose.slides/ifontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering<br/>Läs/skriv [`IFontSubstRuleCollection`](/slides/python-net/sv/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/sv/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>Läs/skriv [`IFontFallBackRulesCollection`](/slides/python-net/sv/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/sv/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Anger om registrerade typsnitt ska föredras framför inbäddade typsnitt med samma namn och stil.<br/>När den är aktiverad ersätts matchande inbäddade typsnitt tillfälligt med motsvarande registrerade typsnitt under export. |

## Metoder

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_substitutions/#) | Hämtar information om typsnitt som kommer att ersättas vid presentationens rendering. |
| [`get_substitutions(self, slides)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_substitutions/#listint) | Hämtar information om typsnitt som kommer att ersättas under rendering av de angivna bilderna. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/sv/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Lägger till det inbäddade typsnittet.<br/>Tänk på att när du kopierar typsnitt är de flesta typsnitt upphovsrättsskyddade. Hitta först licensen för ett typsnitt i förväg och verifiera att de kan överföras fritt till en annan maskin. Ett ArgumentException kan kastas om font data är None eller om detta typsnitt redan är inbäddat |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/sv/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Lägger till det inbäddade typsnittet<br/>Tänk på att när du lägger till typsnitt är de flesta upphovsrättsskyddade. Hitta först licensen för ett typsnitt i förväg och verifiera att de kan överföras fritt till en annan maskin. Ett ArgumentException kan kastas om font data är None eller om detta typsnitt redan är inbäddat |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/sv/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Byt ut typsnitt i presentationen |
| [`replace_font(self, subst_rule)`](/slides/python-net/sv/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Byt ut typsnitt i presentationen med information som tillhandahålls i [`IFontSubstRule`](/slides/python-net/sv/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/sv/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Byt ut typsnitt i presentationen med information som tillhandahålls i samlingen av [`IFontSubstRule`](/slides/python-net/sv/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_fonts/#) | Returnerar typsnitten som används i presentationen |
| [`get_embedded_fonts(self)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Returnerar de inbäddade typsnitten i presentationen |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/sv/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Tar bort det inbäddade typsnittet |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Hämtar bytearrayen som representerar font data för en angiven fontstil och font data. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Bestämmer inbäddningsnivån för ett typsnitt utifrån den givna bytearrayen och typsnittsnamnet. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)