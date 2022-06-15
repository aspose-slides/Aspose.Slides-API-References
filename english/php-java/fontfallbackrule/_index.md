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
| [FontFallBackRule](/php-java/fontfallbackrule/fontfallbackrule/)(long, long, String) | Creates new instance. |
| [FontFallBackRule](/php-java/fontfallbackrule/fontfallbackrule/)(long, long, java.lang.String[]) | Creates new instance. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [addFallBackFonts](/php-java/fontfallbackrule/addfallbackfonts/)(String) | void | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts](/php-java/fontfallbackrule/addfallbackfonts/)(java.lang.String[]) | void | Adds a new fonts to the list of FallBack fonts. |
| [clear](/php-java/fontfallbackrule/clear/)() | void | Removes all fonts from the list. |
| [getCount](/php-java/fontfallbackrule/getcount/)() | int | Gets the number of fonts actually defined for range. Read-only int. |
| [getRangeEndIndex](/php-java/fontfallbackrule/getrangeendindex/)() | long | Get last index of continuous unicode range. |
| [getRangeStartIndex](/php-java/fontfallbackrule/getrangestartindex/)() | long | Get first index of continuous unicode range. |
| [get_Item](/php-java/fontfallbackrule/get_item/)(int) | String | Gets the font name at the specified index. Read-only IFontFallBackRule. |
| [indexOf](/php-java/fontfallbackrule/indexof/)(String) | int | Returns an index of the specified rule in the collection. |
| [remove](/php-java/fontfallbackrule/remove/)(String) | void | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt](/php-java/fontfallbackrule/removeat/)(int) | void | Removes the FallBack font at the specified index of the list. |
| [setRangeEndIndex](/php-java/fontfallbackrule/setrangeendindex/)(long) | void | Get last index of continuous unicode range. |
| [setRangeStartIndex](/php-java/fontfallbackrule/setrangestartindex/)(long) | void | Get first index of continuous unicode range. |
| [toArray](/php-java/fontfallbackrule/toarray/)() | String | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray](/php-java/fontfallbackrule/toarray/)(int, int) | String | Creates and returns an array with all FallBack fonts from the specified range in list. // Create a rule contains a list of fonts. IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman"); // Get a last two font names as array. String[] fontNames = newRule.toArray(2, 2); |
