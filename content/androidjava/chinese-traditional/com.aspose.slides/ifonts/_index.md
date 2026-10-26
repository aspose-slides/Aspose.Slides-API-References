---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Represents fonts collection.
type: docs
url: /zh-hant/com.aspose.slides/ifonts/
---```
public interface IFonts
```

表示字型集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | 返回或設定 Latin 字型。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或設定 Latin 字型。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或設定 東亞 字型。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或設定 東亞 字型。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或設定 複雜文字字型。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或設定 複雜文字字型。 |
| [getScriptFontMap()](#getScriptFontMap--) | 返回簡報中所有腳本字型定義的字典。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 取得簡報佈景主題中與特定腳本標籤相關聯的字型名稱。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 為特定腳本標籤指派字型名稱，定義該腳本的文字在簡報中的呈現方式。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 從佈景主題的字型集合中移除與特定腳本標籤相關聯的字型設定。 |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

返回或設定 Latin 字型。讀/寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

返回或設定 Latin 字型。讀/寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

返回或設定 東亞 字型。讀/寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

返回或設定 東亞 字型。讀/寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

返回或設定 複雜文字字型。讀/寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

返回或設定 複雜文字字型。讀/寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

返回簡報中所有腳本字型定義的字典。

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**返回:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - 映射腳本代碼到字型名稱的字典。

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

從簡報佈景主題取得與特定腳本標籤相關聯的字型名稱。

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | 用於識別書寫系統的 BCP-47 腳本代碼（例如 "Latn", "Cyrl", "Jpan"）。 |

**返回:**
java.lang.String - 指定腳本使用的字型名稱；如果未定義該腳本，則為 null。

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

為特定腳本標籤指定字型名稱，定義該腳本的文字在簡報中的呈現方式。

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | 用於識別書寫系統的 BCP-47 腳本代碼（例如 "Arab", "Hebr", "Hans"）。 |
| fontName | java.lang.String | 要指派給指定腳本的字型名稱。 |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

從佈景主題的字型集合中移除與特定腳本標籤相關聯的字型設定。

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | 要移除其字型設定的 BCP-47 腳本代碼。 |