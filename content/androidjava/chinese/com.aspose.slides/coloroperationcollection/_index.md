---
title: ColorOperationCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示颜色变换操作的集合。
type: docs
url: /zh/com.aspose.slides/coloroperationcollection/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)  
```
public final class ColorOperationCollection implements IColorOperationCollection
```

表示一个颜色变换操作的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中操作的数量。 |
| [get_Item(int index)](#get-Item-int-) | 返回或设置指定索引处的操作。 |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 返回或设置指定索引处的操作。 |
| [add(int operation, float parameter)](#add-int-float-) | 在集合末尾添加一个新操作。 |
| [add(int operation)](#add-int-) | 在集合末尾添加一个新操作。 |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 在集合中插入新操作。 |
| [insert(int position, int operation)](#insert-int-int-) | 在集合中插入新操作。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中删除颜色操作。 |
| [clear()](#clear--) | 删除所有颜色操作。 |
| [iterator()](#iterator--) | 返回一个枚举器，用于遍历集合。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根对象。 |
| [deepClone()](#deepClone--) | 创建一个 ColorOperationCollection 集合的副本。 |
| [cloneT()](#cloneT--) | 克隆当前对象 |

### size() {#size--}
```
public final int size()
```

返回集合中操作的数量。只读 int。

**返回:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

返回或设置指定索引处的操作。读写 [ColorOperation](../../com.aspose.slides/coloroperation)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

返回或设置指定索引处的操作。读写 [ColorOperation](../../com.aspose.slides/coloroperation)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

在集合末尾添加一个新操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |
| parameter | float | 操作的参数。 |

**返回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已添加的操作。

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

在集合末尾添加一个新操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |

**返回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已添加的操作。

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

在集合中插入新操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作类型。 |
| parameter | float | 操作的参数。 |

**返回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

在集合中插入新操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作类型。 |

**返回:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中删除颜色操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的颜色操作的索引。 |

### clear() {#clear--}
```
public final void clear()
```

删除所有颜色操作。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

返回一个枚举器，用于遍历集合。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 整个集合的 java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根对象。只读 Object。

**返回:**  
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

创建一个 ColorOperationCollection 集合的副本。

**返回:**  
java.lang.Object - 新建的 [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) 集合。

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

克隆当前对象

**返回:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - 克隆