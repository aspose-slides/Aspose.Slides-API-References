---
title: Fonts
second_title: Aspose.Slides for Java API 參考
description: 字體集合。
type: docs
url: /zh-hant/com.aspose.slides/fonts/
---
**繼承：**
java.lang.Object

**全部實作的介面：**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

字體集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | 傳回簡報中所有腳本字體定義的字典。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 取得簡報主題中與特定腳本標籤相關聯的字體名稱。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 為特定腳本標籤指定字體名稱，以定義該腳本文字在簡報中的呈現方式。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 從主題的字體集合中移除與特定腳本標籤相關的字體設定。 |
| [getLatinFont()](#getLatinFont--) | 傳回或設定 Latin 字體。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 傳回或設定 Latin 字體。 |
| [getEastAsianFont()](#getEastAsianFont--) | 傳回或設定 East Asian 字體。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 傳回或設定 East Asian 字體。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 傳回或設定 complex script 字體。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 傳回或設定 complex script 字體。 |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


傳回簡報中所有腳本字體定義的字典。

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**傳回：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - 映射腳本代碼到字體名稱的字典。
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```


取得簡報主題中與特定腳本標籤相關聯的字體名稱。

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | 用於辨識書寫系統的 BCP-47 腳本代碼（例如 "Latn", "Cyrl", "Jpan"）。 |

**傳回：**
java.lang.String - 指定腳本使用的字體名稱，如果未定義該腳本則為  null  。

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


為特定腳本標籤指定字體名稱，以定義該腳本文字在簡報中的呈現方式。

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | BCP-47 腳本代碼（例如 "Arab", "Hebr", "Hans"）用於辨識書寫系統。 |
| fontName | java.lang.String | 指定給該腳本的字體名稱。 |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


從主題的字體集合中移除與特定腳本標籤相關的字體設定。

--------------------

> ```
> 此範例示範如何移除希伯來腳本的字體對映：
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | 應移除字體設定的 BCP-47 腳本代碼。 |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


傳回或設定 Latin 字體。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


傳回或設定 Latin 字體。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


傳回或設定 East Asian 字體。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


傳回或設定 East Asian 字體。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


傳回或設定 complex script 字體。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


傳回或設定 complex script 字體。讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |