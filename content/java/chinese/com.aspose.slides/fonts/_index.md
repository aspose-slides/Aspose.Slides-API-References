---
title: Fonts
second_title: Aspose.Slides for Java API 参考
description: 字体集合。
type: docs
url: /zh/com.aspose.slides/fonts/
---
**继承:**
java.lang.Object

**已实现的接口:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

字体集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | 返回演示文稿中所有脚本字体定义的字典。 |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 获取与演示文稿主题中特定脚本标签关联的字体名称。 |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 为特定脚本标签分配字体名称，以定义该脚本的文本在演示文稿中的呈现方式。 |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 从主题的字体集合中移除与特定脚本标签关联的字体设置。 |
| [getLatinFont()](#getLatinFont--) | 返回或设置 Latin 字体。 |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 返回或设置 Latin 字体。 |
| [getEastAsianFont()](#getEastAsianFont--) | 返回或设置 East Asian 字体。 |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 返回或设置 East Asian 字体。 |
| [getComplexScriptFont()](#getComplexScriptFont--) | 返回或设置 complex script 字体。 |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 返回或设置 complex script 字体。 |
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

**返回:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - 将脚本代码映射到字体名称的字典。
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

获取与演示文稿主题中特定脚本标签关联的字体名称。

--------------------

> ```
> 此示例演示如何检索演示文稿主题中分配给西里尔文脚本的字体。
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| script | java.lang.String | 用于标识书写系统的 BCP-47 脚本代码（例如 "Latn", "Cyrl", "Jpan"）。 |

**返回:**
java.lang.String - 用于指定脚本的字体名称，如果未定义该脚本则为  null 。

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

为特定脚本标签分配字体名称，以定义该脚本的文本在演示文稿中的呈现方式。

--------------------

> ```
> 此示例展示如何将阿拉伯文脚本的字体设置为 "Segoe UI"：
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| script | java.lang.String | 用于标识书写系统的 BCP-47 脚本代码（例如 "Arab", "Hebr", "Hans"）。 |
| fontName | java.lang.String | 要分配给指定脚本的字体名称。 |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

从主题的字体集合中移除与特定脚本标签关联的字体设置。

--------------------

> ```
> 此示例演示如何移除希伯来文脚本的字体映射：
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| script | java.lang.String | 要移除其字体设置的 BCP-47 脚本代码。 |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

返回或设置 Latin 字体。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

返回或设置 Latin 字体。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

返回或设置 East Asian 字体。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

返回或设置 East Asian 字体。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

返回或设置 complex script 字体。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

返回或设置 complex script 字体。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |