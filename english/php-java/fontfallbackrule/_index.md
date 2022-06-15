---
title: FontFallBackRule
type: docs
weight: 0
url: /php-java/fontfallbackrule/
---

# FontFallBackRule class

 Represents font fallback rule
 

## Constructors

| name | description |
| --- | --- |
| [FontFallBackRule](/slides/php-java/fontfallbackrule/fontfallbackrule/)(long, long, String) | Creates new instance. |
| [FontFallBackRule](/slides/php-java/fontfallbackrule/fontfallbackrule/)(long, long, java.lang.String[]) | Creates new instance. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [addFallBackFonts](/slides/php-java/fontfallbackrule/addfallbackfonts/)(String) | void | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts](/slides/php-java/fontfallbackrule/addfallbackfonts/)(java.lang.String[]) | void | Adds a new fonts to the list of FallBack fonts. |
| [clear](/slides/php-java/fontfallbackrule/clear/)() | void | Removes all fonts from the list. |
| [getCount](/slides/php-java/fontfallbackrule/getcount/)() | int | Gets the number of fonts actually defined for range. Read-only int. |
| [getRangeEndIndex](/slides/php-java/fontfallbackrule/getrangeendindex/)() | long | Get last index of continuous unicode range. |
| [getRangeStartIndex](/slides/php-java/fontfallbackrule/getrangestartindex/)() | long | Get first index of continuous unicode range. |
| [get_Item](/slides/php-java/fontfallbackrule/get_item/)(int) | String | Gets the font name at the specified index. Read-only IFontFallBackRule. |
| [indexOf](/slides/php-java/fontfallbackrule/indexof/)(String) | int | Returns an index of the specified rule in the collection. |
| [remove](/slides/php-java/fontfallbackrule/remove/)(String) | void | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt](/slides/php-java/fontfallbackrule/removeat/)(int) | void | Removes the FallBack font at the specified index of the list. |
| [setRangeEndIndex](/slides/php-java/fontfallbackrule/setrangeendindex/)(long) | void | Get last index of continuous unicode range. |
| [setRangeStartIndex](/slides/php-java/fontfallbackrule/setrangestartindex/)(long) | void | Get first index of continuous unicode range. |
| [toArray](/slides/php-java/fontfallbackrule/toarray/)() | String | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray](/slides/php-java/fontfallbackrule/toarray/)(int, int) | String | Creates and returns an array with all FallBack fonts from the specified range in list. // Create a rule contains a list of fonts. IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman"); // Get a last two font names as array. String[] fontNames = newRule.toArray(2, 2); |
