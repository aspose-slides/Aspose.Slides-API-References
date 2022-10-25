---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Represents font fallback rule
type: docs
weight: 780
url: /java/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Represents font fallback rule
## Methods

| Method | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Adds a new fonts to the list of FallBack fonts. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Get first index of continuous unicode range. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Get last index of continuous unicode range. |
| [getCount()](#getCount--) | Gets the number of fonts actually defined for range. |
| [get_Item(int index)](#get-Item-int-) | Gets the font name at the specified index. |
| [clear()](#clear--) | Removes all fonts from the list. |
| [remove(String fontName)](#remove-java.lang.String-) | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt(int index)](#removeAt-int-) | Removes the FallBack font at the specified index of the list. |
| [toArray()](#toArray--) | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all FallBack fonts from the specified range in list. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returns an index of the specified rule in the collection. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


Adds a new font(s) to the list of FallBack fonts.

--------------------

> ```
> //Create of new instance of FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Add a second font to the rule 
>  newRule.addFallBackFonts("MS Gothic");
>  //Add a third and fourth fonts to the rule 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


Adds a new fonts to the list of FallBack fonts.

--------------------

> ```
> //Create of new instance of FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Add of another three fonts to the rule 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


Get first index of continuous unicode range.

**Returns:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


Get last index of continuous unicode range.

**Returns:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of fonts actually defined for range.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


Gets the font name at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


Removes all fonts from the list.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


Removes the first occurrence of a specific FallBack font from the list.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Removing of Tahoma from list
>  newRule.remove("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The font's name to remove from the list. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the FallBack font at the specified index of the list.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Removing of Tahoma from list
>  newRule.remove(2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the font to remove. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


Creates and returns an array with all FallBack fonts for this rule.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Get all font-names as array
>  String[] fontNames = newRule.toArray();
> ```

**Returns:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


Creates and returns an array with all FallBack fonts from the specified range in list.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Get a last two font-names as array
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

**Returns:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


Returns an index of the specified rule in the collection.

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Get index of Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font's name to find. |

**Returns:**
int - Index of a font or -1 if font not found in list.
