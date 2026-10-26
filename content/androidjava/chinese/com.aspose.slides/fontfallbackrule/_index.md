---
title: FontFallBackRule
second_title: Aspose.Slides for Android Java API 参考
description: 表示字体回退规则
type: docs
url: /zh/com.aspose.slides/fontfallbackrule/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)  
```
public class FontFallBackRule implements IFontFallBackRule
```

表示字体回退规则  
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | 创建新实例。 |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | 创建新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 向回退字体列表中添加新字体。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 向回退字体列表中添加新字体。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 获取连续 Unicode 区间的起始索引。 |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | 获取连续 Unicode 区间的起始索引。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 获取连续 Unicode 区间的结束索引。 |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | 获取连续 Unicode 区间的结束索引。 |
| [getCount()](#getCount--) | 获取在该范围内实际定义的字体数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的字体名称。 |
| [clear()](#clear--) | 从列表中移除所有字体。 |
| [remove(String fontName)](#remove-java.lang.String-) | 从列表中移除特定回退字体的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 从列表中移除指定索引处的回退字体。 |
| [toArray()](#toArray--) | 创建并返回包含此规则所有回退字体的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回列表中指定范围内所有回退字体的数组。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 返回集合中指定规则的索引。 |

### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


创建新实例。

--------------------

> ```
> // Create new instance of FantFallBackRule with one font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Creates new instance.

--------------------

> ```
> // 创建一个包含两个字体的 FantFallBackRule 新实例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // 创建一个包含多个字体的 FantFallBackRule 新实例。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Adds a new font(s) to the list of FallBack fonts.

--------------------

> ```
> // 创建 FontFallBackRule 的新实例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //添加第二个字体到规则
>  newRule.addFallBackFonts("MS Gothic");
>  //添加第三和第四个字体到规则
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Adds a new fonts to the list of FallBack fonts.

--------------------

> ```
> // 创建 FontFallBackRule 的新实例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // 向规则添加另外三个字体 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Get first index of continuous unicode range.

**Returns:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Get first index of continuous unicode range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Get last index of continuous unicode range.

**Returns:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Get last index of continuous unicode range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Gets the number of fonts actually defined for range. Read-only int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Gets the font name at the specified index. Read-only [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Removes all fonts from the list.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Removes the first occurrence of a specific FallBack font from the list.

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 从列表中移除 Tahoma。
>  newRule.remove("Tahoma");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The font's name to remove from the list. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Removes the FallBack font at the specified index of the list.

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 从列表中移除 Tahoma。
>  newRule.remove(2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the font to remove. |

### toArray() {#toArray--}
```
public final String[] toArray()
```
Creates and returns an array with all FallBack fonts for this rule.

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 获取所有字体名称为数组。
>  String[] fontNames = newRule.toArray();
> ```

**Returns:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Creates and returns an array with all FallBack fonts from the specified range in list.

```
// Create a rule contains a list of fonts.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Get a last two font names as array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

**Returns:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)


返回集合中指定规则的索引。

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Get index of Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 要查找的字体名称。 |

**返回值:**
int - 字体的索引，如果列表中未找到字体则返回 -1。