---
title: ColorOperationCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一组颜色变换操作的集合。
type: docs
url: /zh/com.aspose.slides/coloroperationcollection/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

表示一组颜色变换操作的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | Returns the number of operations in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns or sets the operation at the specified index. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returns or sets the operation at the specified index. |
| [add(int operation, float parameter)](#add-int-float-) | Adds a new operation to the end of collection. |
| [add(int operation)](#add-int-) | Adds a new operation to the end of collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserts the new operation to a collection. |
| [insert(int position, int operation)](#insert-int-int-) | Inserts the new operation to a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the color operation from a collection. |
| [clear()](#clear--) | Removes all color operations. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [deepClone()](#deepClone--) | Creates a copy of a ColorOperationCollection collection. |
| [cloneT()](#cloneT--) | Clones current object |
### size() {#size--}
```
public final int size()
```

返回集合中操作的数量。只读 int。

**返回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

在指定索引处返回或设置操作。读/写 [ColorOperation](../../com.aspose.slides/coloroperation)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

在指定索引处返回或设置操作。读/写 [ColorOperation](../../com.aspose.slides/coloroperation)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

在集合末尾添加一个新操作。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |
| parameter | float | 操作参数。 |

**返回值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 添加的操作。
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

在集合末尾添加一个新操作。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |

**返回值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 添加的操作。
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

将新操作插入集合。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作类型。 |
| parameter | float | 操作参数。 |

**返回值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

将新操作插入集合。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作类型。 |

**返回值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中删除颜色操作。

**参数：**
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

返回一个遍历集合的枚举器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - 用于整个集合的 java.util.Iterator。
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

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值：**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

创建一个 ColorOperationCollection 集合的副本。

**返回值：**
java.lang.Object - 新的 [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) 集合。
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

克隆当前对象

**返回值：**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - 克隆