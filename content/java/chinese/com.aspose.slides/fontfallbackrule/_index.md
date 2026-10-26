---
title: FontFallBackRule
second_title: Aspose.Slides for Java API 参考
description: 表示字体回退规则
type: docs
url: /zh/com.aspose.slides/fontfallbackrule/
---
**Inheritance：**
java.lang.Object

**All Implemented Interfaces：**
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
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 向回退字体列表中添加一个新字体。 |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 向回退字体列表中添加新字体。 |
| [getRangeStartIndex()](#getRangeStartIndex--) | 获取连续 Unicode 范围的起始索引。 |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | 获取连续 Unicode 范围的起始索引。 |
| [getRangeEndIndex()](#getRangeEndIndex--) | 获取连续 Unicode 范围的结束索引。 |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | 获取连续 Unicode 范围的结束索引。 |
| [getCount()](#getCount--) | 获取在范围内实际定义的字体数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的字体名称。 |
| [clear()](#clear--) | 从列表中移除所有字体。 |
| [remove(String fontName)](#remove-java.lang.String-) | 从列表中移除特定回退字体的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除列表中指定索引处的回退字体。 |
| [toArray()](#toArray--) | 创建并返回包含此规则所有回退字体的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回列表中指定范围的所有回退字体数组。 |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 返回集合中指定规则的索引。 |

### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

创建新实例。

--------------------

> ```
> // 创建 FantFallBackRule 的新实例，仅使用一种字体。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // 创建 FantFallBackRule 的新实例，使用多种字体。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | long | Unicode 范围的起始索引 |
| endIndex | long | Unicode 范围的结束索引 |
| fontNames | java.lang.String | 用于回退的字体名称或名称列表（逗号分隔） |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

创建新实例。

--------------------

> ```
> // 创建 FantFallBackRule 的新实例，使用两种字体
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // 创建 FantFallBackRule 的新实例，使用多种字体。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | long | Unicode 范围的起始索引 |
| endIndex | long | Unicode 范围的结束索引 |
| fontNames | java.lang.String[] | 用于回退的字体名称或名称列表（逗号分隔） |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

向回退字体列表中添加一个新字体。

--------------------

> ```
> // 创建 FontFallBackRule 的新实例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // 向规则添加第二种字体
>  newRule.addFallBackFonts("MS Gothic");
>  // 向规则添加第三种和第四种字体
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 用于回退的字体名称或名称（逗号分隔） |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

向回退字体列表中添加新字体。

--------------------

> ```
> //创建 FontFallBackRule 的新实例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //向规则添加另外三个字体 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontNames | java.lang.String[] | 用于回退的字体名称或名称列表（逗号分隔） |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

获取连续 Unicode 范围的起始索引。

**返回：**
long

### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

获取连续 Unicode 范围的起始索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

获取连续 Unicode 范围的结束索引。

**返回：**
long

### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

获取连续 Unicode 范围的结束索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

获取在范围内实际定义的字体数量。只读 int。

**返回：**
int

### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

获取指定索引处的字体名称。只读 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
java.lang.String

### clear() {#clear--}
```
public final void clear()
```

从列表中移除所有字体。

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

从列表中移除特定回退字体的第一次出现。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 从列表中移除 Tahoma。
>  newRule.remove("Tahoma");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 要从列表中移除的字体名称。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除列表中指定索引处的回退字体。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //从列表中移除 Tahoma。
>  newRule.remove(2);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的字体的零基索引。 |

### toArray() {#toArray--}
```
public final String[] toArray()
```

创建并返回包含此规则所有回退字体的数组。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 将所有字体名称获取为数组。
>  String[] fontNames = newRule.toArray();
> ```

**返回：**
java.lang.String[] - Array of String

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

创建并返回列表中指定范围的所有回退字体数组。

```
// 创建一个包含字体列表的规则.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // 获取最后两个字体名称作为数组.
 String[] fontNames = newRule.toArray(2, 2);
```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要添加的第一个字体的索引。 |
| count | int | 要添加的字体数量。 |

**返回：**
java.lang.String[] - Array of String

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

返回集合中指定规则的索引。

--------------------

> ```
> // 创建一个包含字体列表的规则.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 获取 Tahoma 的索引.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 要查找的字体名称。 |

**返回：**
int - 字体的索引，如果列表中未找到字体则返回 -1。