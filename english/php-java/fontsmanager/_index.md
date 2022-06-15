---
title: FontsManager
type: docs
weight: 0
url: /php-java/fontsmanager/
---

# FontsManager class

 Manages fonts across the presentation.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addEmbeddedFont](/slides/php-java/fontsmanager/addembeddedfont/)(IFontData, int) | void | Adds the embedded font |
| [addEmbeddedFont](/slides/php-java/fontsmanager/addembeddedfont/)(byte[], int) | void | Adds the embedded font |
| [getEmbeddedFonts](/slides/php-java/fontsmanager/getembeddedfonts/)() | IFontData | Returns the fonts embedded in the presentation |
| [getFontFallBackRulesCollection](/slides/php-java/fontsmanager/getfontfallbackrulescollection/)() | IFontFallBackRulesCollection | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |
| [getFontSubstRuleList](/slides/php-java/fontsmanager/getfontsubstrulelist/)() | IFontSubstRuleCollection | Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |
| [getFonts](/slides/php-java/fontsmanager/getfonts/)() | IFontData | Returns the fonts used in the presentation |
| [removeEmbeddedFont](/slides/php-java/fontsmanager/removeembeddedfont/)(IFontData) | void | Removes the embedded font |
| [replaceFont](/slides/php-java/fontsmanager/replacefont/)(IFontData, IFontData) | void | Replace font in presentation |
| [replaceFont](/slides/php-java/fontsmanager/replacefont/)(IFontSubstRule) | void | Replace font in presentation using information provided in FontSubstRule |
| [replaceFont](/slides/php-java/fontsmanager/replacefont/)(IFontSubstRuleCollection) | void | Replace font in presentation using information provided in collection of FontSubstRule |
| [setFontFallBackRulesCollection](/slides/php-java/fontsmanager/setfontfallbackrulescollection/)(IFontFallBackRulesCollection) | void | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write IFontFallBackRulesCollection. |
| [setFontSubstRuleList](/slides/php-java/fontsmanager/setfontsubstrulelist/)(IFontSubstRuleCollection) | void | Font substitutions to use when rendering. Read/write IFontSubstRuleCollection. |
