---
title: IFontsManager class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ifontsmanager/
---
## IFontsManager klass

Hantera typsnitt i hela presentationen.

IFontsManager-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/sv/aspose.slides/ifontsmanager/font_subst_rule_list/) | Typsnittsersättningar att använda vid rendering<br/>            Läs/skriv [`IFontSubstRuleCollection`](/slides/python-net/sv/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/sv/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Representerar en användares samling av FontFallBack-regler för hantering av typsnittssamlingar för korrekta ersättningar via fallback-funktionalitet<br/>            Läs/skriv [`IFontFallBackRulesCollection`](/slides/python-net/sv/aspose.slides/ifontfallbackrulescollection). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_substitutions/#) | Hämtar information om typsnitt som kommer att ersättas vid presentationens rendering. |
| [`get_substitutions(self, slides)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_substitutions/#listint) | Hämtar information om typsnitt som kommer att ersättas under rendering av de angivna bilderna. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/sv/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Lägger till det inbäddade teckensnittet.<br/>            Tänk på att när du kopierar typsnitt är de flesta skyddade av upphovsrätt. Lokalisera licensen för <br/>            ett teckensnitt i förväg och verifiera att de kan överföras fritt till en annan maskin. Ett ArgumentException kan kastas om teckensnittsdata är None eller om teckensnittet redan är inbäddat |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/sv/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Lägger till det inbäddade teckensnittet.<br/>            Tänk på att när du lägger till typsnitt är de flesta skyddade av upphovsrätt. Lokalisera licensen för <br/>            ett teckensnitt i förväg och verifiera att de kan överföras fritt till en annan maskin. Ett ArgumentException kan kastas om teckensnittsdata är None eller om teckensnittet redan är inbäddat |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/sv/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Ersätt typsnitt i presentationen |
| [`replace_font(self, subst_rule)`](/slides/python-net/sv/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Ersätt typsnitt i presentationen med information som tillhandahålls i [`IFontSubstRule`](/slides/python-net/sv/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/sv/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Ersätt typsnitt i presentationen med information som tillhandahålls i samlingen av [`IFontSubstRule`](/slides/python-net/sv/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_fonts/#) | Returnerar teckensnitten som används i presentationen |
| [`get_embedded_fonts(self)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Returnerar teckensnitten som är inbäddade i presentationen |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/sv/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Tar bort det inbäddade teckensnittet |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Hämtar byte-arrayen som representerar typsnittsdata för en specificerad typsnittsstil och typsnittsdatan. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/sv/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Bestämmer inbäddningsnivån för ett typsnitt från den givna byte-arrayen och typsnittsnamnet. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)