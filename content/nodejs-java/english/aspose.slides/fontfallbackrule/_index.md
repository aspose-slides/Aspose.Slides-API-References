---
title: FontFallBackRule
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/fontfallbackrule/
---

## FontFallBackRule class

 Represents font fallback rule
 

## Functions

| Name | Description |
| --- | --- |
| [FontFallBackRule](fontfallbackrule)(long, long, String) | Creates new instance. |
| [FontFallBackRule](fontfallbackrule)(long, long, java.lang.String[]) | Creates new instance. |

## Functions

| Name | Description |
| --- | --- |
| [addFallBackFonts](addfallbackfonts)(String) | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts](addfallbackfonts)(java.lang.String[]) | Adds a new fonts to the list of FallBack fonts. |
| [clear](clear)() | Removes all fonts from the list. |
| [getCount](getcount)() | Gets the number of fonts actually defined for range. Read-only int. |
| [getRangeEndIndex](getrangeendindex)() | Get last index of continuous unicode range. |
| [getRangeStartIndex](getrangestartindex)() | Get first index of continuous unicode range. |
| [get_Item](get_item)(int) | Gets the font name at the specified index. Read-only IFontFallBackRule. |
| [indexOf](indexof)(String) | Returns an index of the specified rule in the collection. |
| [remove](remove)(String) | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt](removeat)(int) | Removes the FallBack font at the specified index of the list. |
| [setRangeEndIndex](setrangeendindex)(long) | Get last index of continuous unicode range. |
| [setRangeStartIndex](setrangestartindex)(long) | Get first index of continuous unicode range. |
| [toArray](toarray)() | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray](toarray)(int, int) | Creates and returns an array with all FallBack fonts from the specified range in list. // Create a rule contains a list of fonts. IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman"); // Get a last two font names as array. String[] fontNames = newRule.toArray(2, 2); |
