---
title: SmartArtShapeCollection
second_title: Aspose.Slides for Android Java API 参考
description: 表示 SmartArt 形状的集合
type: docs
url: /zh/com.aspose.slides/smartartshapecollection/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

表示 SmartArt 形状的集合

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定的数组。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |

### size() {#size--}
```
public final int size()
```

获取集合中实际包含的元素数量。只读 int。

**返回值:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

获取指定索引处的元素。只读 [SmartArtShape](../../com.aspose.slides/smartartshape)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 形状的索引 |

**返回值:**  
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - SmartArt 形状

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回值:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值:**  
java.lang.Object

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定的数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

返回一个遍历集合的枚举器。

**返回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - 可用于遍历集合的 IGenericEnumerator

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - 整个集合的 java.util.Iterator