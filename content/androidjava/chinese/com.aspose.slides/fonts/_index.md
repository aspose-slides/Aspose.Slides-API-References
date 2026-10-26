---
title: Fonts
second_title: Aspose.Slides 的 Android 通过 Java API 参考
description: 字体集合。
type: docs
url: /zh/com.aspose.slides/fonts/
---
**继承:**  
java.lang.Object

**所有已实现的接口:**  
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

字体集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | 返回演示文稿中所有脚本字体定义的字典。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 获取演示文稿主题中与特定脚本标签关联的字体名称。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 为特定脚本标签分配字体名称，以定义该脚本的文本在演示文稿中的呈现方式。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 从主题的字体集合中移除与特定脚本标签关联的字体设置。 |
| [getLatinFont()](#getLatinFont--) | 返回或设置拉丁字体。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或设置拉丁字体。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或设置东亚字体。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或设置东亚字体。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或设置复杂脚本字体。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或设置复杂脚本字体。 |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

返回演示文稿中所有脚本字体定义的字典。

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

返回或设置复杂脚本字体。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |