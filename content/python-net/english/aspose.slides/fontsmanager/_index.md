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
| [font_subst_rule_list](/slides/python-net/aspose.slides/fontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering.<br/>            Read/write <br/>[`IFontSubstRuleCollection`](/slides/python-net/aspose.slides/ifontsubstrulecollection). |
| [font_fall_back_rules_collection](/slides/python-net/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Read/write <br/>[`IFontFallBackRulesCollection`](/slides/python-net/aspose.slides/ifontfallbackrulescollection). |

## Methods

| Method | Description |
| :- | :- |
| [add_embedded_font](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#IFontData-aspose.slides.export.EmbedFontCharacters/) | Adds the embedded font<br/>            <br/>Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.<br/>An ArgumentException can be thrown if font data is null or this font is already embedded |
| [add_embedded_font](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#bytes-aspose.slides.export.EmbedFontCharacters/) | Adds the embedded font<br/>            <br/>Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of <br/>            a font before hand and verify they can be freely transferred to another machine.<br/>An ArgumentException can be thrown if font data is null or this font is already embedded |
| [replace_font](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#IFontData-IFontData/) | Replace font in presentation |
| [replace_font](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#IFontSubstRule/) | Replace font in presentation using information provided in <br/>[`FontSubstRule`](/slides/python-net/aspose.slides/fontsubstrule) |
| [replace_font](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#IFontSubstRuleCollection/) | Replace font in presentation using information provided in collection of <br/>[`FontSubstRule`](/slides/python-net/aspose.slides/fontsubstrule) |
| [get_fonts](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#/) | Returns the fonts used in the presentation |
| [get_substitutions](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#/) | Gets the information about fonts that will be replaced on the presentation's rendering. |
| [get_embedded_fonts](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#/) | Returns the fonts embedded in the presentation |
| [remove_embedded_font](/slides/python-net/aspose.slides/fontsmanager/fontsmanager/#IFontData/) | Removes the embedded font |

