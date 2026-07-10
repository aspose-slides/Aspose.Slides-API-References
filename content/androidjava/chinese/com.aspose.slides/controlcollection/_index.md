---
title: ControlCollection
second_title: Aspose.Slides for Android via Java API 参考
description: ActiveX 控件的集合。
type: docs
url: /zh/com.aspose.slides/controlcollection/
---
**继承：**
java.lang.Object

**全部实现的接口：**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```java
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX 控件的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中对象的数量。 |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 创建并将新控件添加到集合中。 |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | 从集合中移除 ActiveX 控件。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中移除位于指定位置的 ActiveX 控件。 |
| [clear()](#clear--) | 从集合中移除所有控件。 |
| [get_Item(int index)](#get-Item-int-) | 返回位于指定位置的控件。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将整个集合复制到指定的数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

返回集合中对象的数量。只读 int。

**返回：**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

创建并将新控件添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| controlType | int | 要添加的控件类型。 |
| x | float | 形状框左侧的 X 坐标。 |
| y | float | 形状框上侧的 Y 坐标。 |
| width | float | 形状框的宽度。 |
| height | float | 形状框的高度。 |

**返回：**
[IControl](../../com.aspose.slides/icontrol) - 已创建的控件。

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

从集合中移除 ActiveX 控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 要移除的控件。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中移除位于指定位置的 ActiveX 控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的控件的索引。 |

### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有控件。

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

返回位于指定位置的控件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 控件的索引。 |

**返回：**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - 整个集合的 java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将整个集合复制到指定的数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组 |
| index | int | 目标数组中的索引。 |

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

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject