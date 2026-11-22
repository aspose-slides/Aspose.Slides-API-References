---
title: IFontsManager class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ifontsmanager/
---
## IFontsManager klasse

Beheert lettertypen in de gehele presentatie.

Het IFontsManager-type biedt de volgende leden:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/nl/aspose.slides/ifontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering<br/>            Lezen/schrijven [`IFontSubstRuleCollection`](/slides/python-net/nl/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/nl/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Lezen/schrijven [`IFontFallBackRulesCollection`](/slides/python-net/nl/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/nl/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Specifies whether registered fonts should be preferred over embedded fonts with the same font name and style.<br/>            When enabled, matching embedded fonts are temporarily replaced with corresponding registered fonts during export. |

## Methoden

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_substitutions/#) | Haalt de informatie op over fonts that will be replaced on the presentation's rendering. |
| [`get_substitutions(self, slides)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_substitutions/#listint) | Haalt de informatie op over fonts that will be replaced during rendering of the specified slides. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Voegt het embedded font toe.<br/>            Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/nl/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Voegt het embedded font toe<br/>            Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/nl/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Vervang font in presentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/nl/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Vervang font in presentation using information provided in [`IFontSubstRule`](/slides/python-net/nl/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/nl/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Vervang font in presentation using information provided in collection of [`IFontSubstRule`](/slides/python-net/nl/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_fonts/#) | Retourneert de fonts used in the presentation |
| [`get_embedded_fonts(self)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Retourneert de fonts embedded in the presentation |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/nl/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Verwijdert de embedded font |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Retrieves the byte array representing the font data for a specified font style and font data. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/nl/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Determines the embedding level of a font from the given byte array and font name. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)