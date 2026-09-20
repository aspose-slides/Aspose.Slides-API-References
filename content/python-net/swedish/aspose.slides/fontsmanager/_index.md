---
title: FontsManager class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/fontsmanager/
---
## FontsManager klass

Hantera typsnitt i hela presentationen.

FontsManager-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/sv/aspose.slides/fontsmanager/font_subst_rule_list/) | Typsnittsubstitutioner att använda vid rendering.<br/>            Läs/skriv [`IFontSubstRuleCollection`](/slides/python-net/sv/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/sv/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Representerar en användares samling av FontFallBack-regler för hantering av samlingar av typsnitt för korrekta substitutioner via reservfunktion.<br/>            Läs/skriv [`IFontFallBackRulesCollection`](/slides/python-net/sv/aspose.slides/ifontfallbackrulescollection). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/sv/aspose.slides/fontsmanager/get_substitutions/#) | Hämtar information om typsnitt som kommer att ersättas vid presentationens rendering. |
| [`get_substitutions(self, slides)`](/slides/python-net/sv/aspose.slides/fontsmanager/get_substitutions/#listint) | Hämtar information om typsnitt som kommer att ersättas under rendering av de angivna bilderna. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/sv/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Lägger till det inbäddade typsnittet<br/>            Tänk på att de flesta typsnitt är upphovsrättsskyddade när du kopierar dem. Lokalisera först licensen för <br/>            ett typsnitt i förväg och verifiera att de får överföras fritt till en annan maskin. Ett ArgumentException kan kastas om font data är None eller detta typsnitt redan är inbäddat |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/sv/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Lägger till det inbäddade typsnittet<br/>            Tänk på att de flesta typsnitt är upphovsrättsskyddade när du kopierar dem. Lokalisera först licensen för <br/>            ett typsnitt i förväg och verifiera att de får överföras fritt till en annan maskin. Ett ArgumentException kan kastas om font data är None eller detta typsnitt redan är inbäddat |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/sv/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Ersätt typsnitt i presentationen |
| [`replace_font(self, subst_rule)`](/slides/python-net/sv/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Ersätt typsnitt i presentationen med hjälp av information som tillhandahålls i [`FontSubstRule`](/slides/python-net/sv/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/sv/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Ersätt typsnitt i presentationen med hjälp av information som tillhandahålls i samlingen av [`FontSubstRule`](/slides/python-net/sv/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/sv/aspose.slides/fontsmanager/get_fonts/#) | Returnerar de typsnitt som används i presentationen |
| [`get_embedded_fonts(self)`](/slides/python-net/sv/aspose.slides/fontsmanager/get_embedded_fonts/#) | Returnerar de inbäddade typsnitten i presentationen |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/sv/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Tar bort det inbäddade typsnittet |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/sv/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Hämtar byte-arrayen som representerar font data för en specificerad fontstil och font data. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/sv/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Bestämmer inbäddningsnivån för ett typsnitt från den givna byte-arrayen och typsnittsnamnet. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)