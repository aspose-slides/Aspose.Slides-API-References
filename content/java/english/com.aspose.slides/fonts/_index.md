---
title: Fonts
second_title: Aspose.Slides for Java API Reference
description: Fonts collection.
type: docs
url: /com.aspose.slides/fonts/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Fonts collection.
## Methods

| Method | Description |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Returns a dictionary of all script font definitions in the presentation. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Gets the font name associated with a specific script tag from the presentation theme. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Removes the font setting associated with a specific script tag from the theme's font collection. |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Returns a dictionary of all script font definitions in the presentation.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```


Gets the font name associated with a specific script tag from the presentation theme.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | The BCP-47 script code (e.g., "Latn", "Cyrl", "Jpan") used to identify a writing system. |

**Returns:**
java.lang.String - The name of the font used for the specified script, or  null  if the script is not defined.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | The BCP-47 script code (e.g., "Arab", "Hebr", "Hans") identifying the writing system. |
| fontName | java.lang.String | The name of the font to assign to the specified script. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Removes the font setting associated with a specific script tag from the theme's font collection.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | The BCP-47 script code whose font setting should be removed. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Returns or sets the Latin font. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Returns or sets the Latin font. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Returns or sets the East Asian font. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Returns or sets the East Asian font. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Returns or sets the complex script font. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Returns or sets the complex script font. Read/write [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

