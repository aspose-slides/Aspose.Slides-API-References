---
title: FontsManager
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/fontsmanager/
---


FontsManager class

Manages fonts across the presentation.

The FontsManager type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [font_subst_rule_list](/slides/python-net/aspose.slides/fontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering.<br/>            Read/write [`IFontSubstRuleCollection`](/slides/python-net/aspose.slides/ifontsubstrulecollection). |
| [font_fall_back_rules_collection](/slides/python-net/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Read/write [`IFontFallBackRulesCollection`](/slides/python-net/aspose.slides/ifontfallbackrulescollection). |

## Methods

| Method | Description |
| :- | :- |
| [add_embedded_font](/slides/python-net/aspose.slides/fontsmanager/add_embedded_font/#IFontData-aspose.slides.export.EmbedFontCharacters/) | Adds the embedded font<br/>            Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is null or this font is already embedded |
| [add_embedded_font](/slides/python-net/aspose.slides/fontsmanager/add_embedded_font/#bytes-aspose.slides.export.EmbedFontCharacters/) | Adds the embedded font<br/>            Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is null or this font is already embedded |
| [replace_font](/slides/python-net/aspose.slides/fontsmanager/replace_font/#IFontData-IFontData/) | Replace font in presentation |
| [replace_font](/slides/python-net/aspose.slides/fontsmanager/replace_font/#IFontSubstRule/) | Replace font in presentation using information provided in [`FontSubstRule`](/slides/python-net/aspose.slides/fontsubstrule) |
| [replace_font](/slides/python-net/aspose.slides/fontsmanager/replace_font/#IFontSubstRuleCollection/) | Replace font in presentation using information provided in collection of [`FontSubstRule`](/slides/python-net/aspose.slides/fontsubstrule) |
| [get_fonts](/slides/python-net/aspose.slides/fontsmanager/get_fonts/#/) | Returns the fonts used in the presentation |
| [get_substitutions](/slides/python-net/aspose.slides/fontsmanager/get_substitutions/#/) | Gets the information about fonts that will be replaced on the presentation's rendering. |
| [get_embedded_fonts](/slides/python-net/aspose.slides/fontsmanager/get_embedded_fonts/#/) | Returns the fonts embedded in the presentation |
| [remove_embedded_font](/slides/python-net/aspose.slides/fontsmanager/remove_embedded_font/#IFontData/) | Removes the embedded font |

