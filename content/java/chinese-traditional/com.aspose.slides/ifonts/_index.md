---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: 表示字體集合。
type: docs
url: /zh-hant/com.aspose.slides/ifonts/
---```
public interface IFonts
```

表示字體集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | 返回或設定拉丁字體。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或設定拉丁字體。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或設定東亞字體。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或設定東亞字體。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或設定複雜腳本字體。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或設定複雜腳本字體。 |
| [getScriptFontMap()](#getScriptFontMap--) | 返回簡報中所有腳本字體定義的字典。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 取得簡報主題中與特定腳本標籤相關聯的字體名稱。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 將字體名稱指派給特定腳本標籤，以定義簡報中該腳本文字的呈現方式。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 從主題的字體集合中移除與特定腳本標籤相關聯的字體設定。 |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


返回或設定 Latin 字體。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


返回或設定 Latin 字體。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


返回或設定 東亞字體。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


返回或設定 東亞字體。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


返回或設定 複雜腳本字體。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


返回或設定 複雜腳本字體。可讀寫 [IFontData](../../com.aspose.slides/ifontdata)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


返回簡報中所有腳本字體定義的字典。

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**返回：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - 將腳本代碼映射到字體名稱的字典。
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
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
| script | java.lang.String | 用於識別書寫系統的 BCP-47 腳本代碼（例如，"Latn"、"Cyrl"、"Jpan"）。 |

**返回：**
java.lang.String - 指定腳本使用的字體名稱，如果未定義該腳本則為  null .

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


將字體名稱指派給特定腳本標籤，以定義簡報中該腳本文字的呈現方式。

--------------------

> ```
> 本範例示範如何將阿拉伯腳本的字體設定為 "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | 用於識別書寫系統的 BCP-47 腳本代碼（例如，"Arab"、"Hebr"、"Hans"）。 |
| fontName | java.lang.String | 指派給指定腳本的字體名稱。 |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


從主題的字體集合中移除與特定腳本標籤相關聯的字體設定。

--------------------

> ```
> 此範例示範如何移除希伯來腳本的字體映射：
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| script | java.lang.String | 要移除其字體設定的 BCP-47 腳本代碼。 |