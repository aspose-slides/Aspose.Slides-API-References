---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Represents font fallback rule
type: docs
url: /zh/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

表示字体回退规则
## 方法

| 方法 | 描述 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Adds a new fonts to the list of FallBack fonts. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Get first index of continuous unicode range. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Get last index of continuous unicode range. |
| [getCount()](#getCount--) | Gets the number of fonts actually defined for range. |
| [get_Item(int index)](#get-Item-int-) | Gets the font name at the specified index. |
| [clear()](#clear--) | Removes all fonts from the list. |
| [remove(String fontName)](#remove-java.lang.String-) | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt(int index)](#removeAt-int-) | Removes the FallBack font at the specified index of the list. |
| [toArray()](#toArray--) | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all FallBack fonts from the specified range in list. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returns an index of the specified rule in the collection. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


向 FallBack 字体列表中添加新字体。

--------------------

> ```
> //创建 FantFallBackRule 的新实例
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //向规则添加第二个字体 
>  newRule.addFallBackFonts("MS Gothic");
>  //向规则添加第三个和第四个字体 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | FallBack 字体的名称或多个名称（逗号分隔） |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


向 FallBack 字体列表中添加新字体。

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
| fontNames | java.lang.String[] | FallBack 字体的名称或多个名称（逗号分隔） |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


获取连续 Unicode 范围的起始索引。

**返回值：**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


获取连续 Unicode 范围的结束索引。

**返回值：**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


获取在范围内实际定义的字体数量。

**返回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


获取指定索引处的字体名称。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


删除列表中的所有字体。

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


从列表中删除首次出现的指定 FallBack 字体。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //从列表中删除 Tahoma
>  newRule.remove("Tahoma");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 要从列表中删除的字体名称。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


删除列表中指定索引处的 FallBack 字体。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //从列表中删除 Tahoma
>  newRule.remove(2);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的字体的零基索引。 |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


创建并返回包含此规则所有 FallBack 字体的数组。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //获取所有字体名称为数组
>  String[] fontNames = newRule.toArray();
> ```

**返回值：**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


创建并返回列表中指定范围内所有 FallBack 字体的数组。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //获取最后两个字体名称为数组
>  String[] fontNames = newRule.toArray(2,2);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 第一个要添加的字体的索引。 |
| count | int | 要添加的字体数量。 |

**返回值：**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


返回集合中指定规则的索引。

--------------------

> ```
> // 创建一个包含字体列表的规则。
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //获取 Tahoma 的索引
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 要查找的字体名称。 |

**返回值：**
int - 字体的索引；如果未在列表中找到字体则返回 -1。