---
title: IFontsManager class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description:
type: docs
url: /fa/aspose.slides/ifontsmanager/
---
## IFontsManager کلاس

Manages fonts across the presentation.

The IFontsManager type exposes the following members:

## خصوصیات

| ویژگی | توضیح |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/fa/aspose.slides/ifontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering<br/>            خواندنی/نوشتنی [`IFontSubstRuleCollection`](/slides/python-net/fa/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/fa/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            خواندنی/نوشتنی [`IFontFallBackRulesCollection`](/slides/python-net/fa/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/fa/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Specifies whether registered fonts should be preferred over embedded fonts with the same font name and style.<br/>            When enabled, matching embedded fonts are temporarily replaced with corresponding registered fonts during export. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_substitutions/#) | Gets the information about fonts that will be replaced on the presentation's rendering. |
| [`get_substitutions(self, slides)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_substitutions/#listint) | Gets the information about fonts that will be replaced during rendering of the specified slides. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Adds the embedded font.<br/>            Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/fa/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Adds the embedded font<br/>            Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is None or this font is already embedded |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/fa/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Replace font in presentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/fa/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Replace font in presentation using information provided in [`IFontSubstRule`](/slides/python-net/fa/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/fa/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Replace font in presentation using information provided in collection of [`IFontSubstRule`](/slides/python-net/fa/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_fonts/#) | Returns the fonts used in the presentation |
| [`get_embedded_fonts(self)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Returns the fonts embedded in the presentation |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/fa/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Removes the embedded font |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Retrieves the byte array representing the font data for a specified font style and font data. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/fa/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Determines the embedding level of a font from the given byte array and font name. |


### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)