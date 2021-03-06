---
title: FontsManager
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 4480
url: /net/aspose.slides/fontsmanager/
---
## FontsManager class

Manages fonts across the presentation.

```csharp
public class FontsManager : IFontsManager
```

## Properties

| Name | Description |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/fontsmanager/fontfallbackrulescollection) { get; set; } | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/fontsmanager/fontsubstrulelist) { get; set; } | Font substitutions to use when rendering. Read/write [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |

## Methods

| Name | Description |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont)(byte[], EmbedFontCharacters) | Adds the embedded font Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is null or this font is already embedded |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont)(IFontData, EmbedFontCharacters) | Adds the embedded font Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine.An ArgumentException can be thrown if font data is null or this font is already embedded |
| [GetEmbeddedFonts](../../aspose.slides/fontsmanager/getembeddedfonts)() | Returns the fonts embedded in the presentation |
| [GetFonts](../../aspose.slides/fontsmanager/getfonts)() | Returns the fonts used in the presentation |
| [RemoveEmbeddedFont](../../aspose.slides/fontsmanager/removeembeddedfont)(IFontData) | Removes the embedded font |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont)(IFontSubstRule) | Replace font in presentation using information provided in [`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont)(IFontSubstRuleCollection) | Replace font in presentation using information provided in collection of [`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont)(IFontData, IFontData) | Replace font in presentation |

### See Also

* interface [IFontsManager](../ifontsmanager)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
