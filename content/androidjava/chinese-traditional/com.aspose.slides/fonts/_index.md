---
title: Fonts
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 字型集合。
type: docs
url: /zh-hant/com.aspose.slides/fonts/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

字型集合。
## 方法

| Method | Description |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | 傳回簡報中所有腳本字型定義的字典。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 從簡報主題取得與特定腳本標籤關聯的字型名稱。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 指派字型名稱給特定腳本標籤，以定義簡報中該腳本文字的呈現方式。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 從主題的字型集合中移除與特定腳本標籤關聯的字型設定。 |
| [getLatinFont()](#getLatinFont--) | 傳回或設定拉丁字型。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 傳回或設定拉丁字型。 |
| [getEastAsianFont()](#getEastAsianFont--) | 傳回或設定東亞字型。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 傳回或設定東亞字型。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 傳回或設定複雜腳本字型。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 傳回或設定複雜腳本字型。 |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

傳回簡報中所有腳本字型定義的字典。

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**傳回值：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - 將腳本代碼對映到字型名稱的字典。
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

從簡報主題取得與特定腳本標籤關聯的字型名稱。

--------------------

> ```
> 此範例示範如何在簡報主題中取得指派給西里爾文字的字型。
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| script | java.lang.String | 用於識別書寫系統的 BCP-47 腳本代碼（例如 "Latn"、"Cyrl"、"Jpan"）。 |

**傳回值：**
java.lang.String - 指定腳本使用的字型名稱；如果未定義該腳本，則為 null。
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

指派字型名稱給特定腳本標籤，以定義簡報中該腳本文字的呈現方式。

--------------------

> ```
> 此範例說明如何將阿拉伯文字的字型設定為 "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| script | java.lang.String | 用於識別書寫系統的 BCP-47 腳本代碼（例如 "Arab"、"Hebr"、"Hans"）。 |
| fontName | java.lang.String | 要指派給指定腳本的字型名稱。 |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

從主題的字型集合中移除與特定腳本標籤關聯的字型設定。

--------------------

> ```
> 此範例示範如何移除希伯來文字的字型映射：
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| script | java.lang.String | 要移除其字型設定的 BCP-47 腳本代碼。 |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

傳回或設定拉丁字型。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回值：**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

傳回或設定拉丁字型。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

傳回或設定東亞字型。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回值：**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

傳回或設定東亞字型。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

傳回或設定複雜腳本字型。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回值：**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

傳回或設定複雜腳本字型。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |