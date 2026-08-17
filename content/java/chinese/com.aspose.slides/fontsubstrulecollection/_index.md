---
title: FontSubstRuleCollection
second_title: Aspose.Slides 的 Java API 参考
description: 表示字体替换的集合。
type: docs
url: /zh/com.aspose.slides/fontsubstrulecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

表示字体替换的集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | 将新的字体替换规则添加到集合中 |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | 从集合中移除特定对象的第一次出现。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


获取集合中实际包含的元素数量。只读 int。

**返回：**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


将新的字体替换规则添加到集合中

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


从集合中移除特定对象的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 要从集合中移除的字体替换规则。 |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


获取指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - 用于遍历整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


将集合中的所有元素复制到指定数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


返回同步根。只读 Object。

**返回：**
java.lang.Object