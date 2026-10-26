---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /zh/com.aspose.slides/ifonts/
---```
public interface IFonts
```

表示字体集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | 返回或设置拉丁字体。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或设置拉丁字体。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或设置东亚字体。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或设置东亚字体。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或设置复杂脚本字体。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或设置复杂脚本字体。 |
| [getScriptFontMap()](#getScriptFontMap--) | 返回演示文稿中所有脚本字体定义的字典。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 获取演示文稿主题中与特定脚本标签关联的字体名称。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 为特定脚本标签分配字体名称，以定义该脚本的文本在演示文稿中的呈现方式。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 从主题的字体集合中移除与特定脚本标签关联的字体设置。 |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


返回或设置拉丁字体。读取/写入 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


返回或设置拉丁字体。读取/写入 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


返回或设置东亚字体。读取/写入 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


返回或设置东亚字体。读取/写入 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


返回或设置复杂脚本字体。读取/写入 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


返回或设置复杂脚本字体。读取/写入 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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


**返回：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


获取演示文稿主题中与特定脚本标签关联的字体名称。

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | 用于标识书写系统的 BCP-47 脚本代码（例如 "Latn", "Cyrl", "Jpan"） |
  
**返回：**
java.lang.String - 指定脚本使用的字体名称，如果未定义该脚本，则为  null  .
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


为特定脚本标签分配字体名称，以定义该脚本的文本在演示文稿中的呈现方式。

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | 用于标识书写系统的 BCP-47 脚本代码（例如 "Arab", "Hebr", "Hans"） |
| fontName | java.lang.String | 要分配给指定脚本的字体名称 |
  
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


从主题的字体集合中移除与特定脚本标签关联的字体设置。

--------------------

> ```
> 此示例演示如何移除希伯来文脚本的字体映射：
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | 要移除其字体设置的 BCP-47 脚本代码 |