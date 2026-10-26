---
title: ControlCollection
second_title: Aspose.Slides for Android via Java API 參考
description: ActiveX 控制項的集合。
type: docs
url: /zh-hant/com.aspose.slides/controlcollection/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject  
```
public class ControlCollection implements IControlCollection, IDOMObject
```

ActiveX 控制項的集合。

## Methods

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 傳回集合中物件的數量。 |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 建立並將新控制項加入集合。 |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | 從集合中移除 ActiveX 控制項。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除位於指定位置的 ActiveX 控制項。 |
| [clear()](#clear--) | 從集合中移除所有控制項。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定位置的控制項。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將整個集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

傳回集合中物件的數量。唯讀 int.

**傳回：**  
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

建立並將新控制項加入集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| controlType | int | 要新增的控制項類型。 |
| x | float | 形狀框左側的 X 坐標。 |
| y | float | 形狀框上側的 Y 坐標。 |
| width | float | 形狀框的寬度。 |
| height | float | 形狀框的高度。 |

**傳回：**  
[IControl](../../com.aspose.slides/icontrol) - 已建立的控制項。

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

從集合中移除 ActiveX 控制項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 要移除的控制項。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中移除位於指定位置的 ActiveX 控制項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的控制項索引。 |

### clear() {#clear--}
```
public final void clear()
```

移除所有控制項。

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

傳回指定位置的控制項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 控制項的索引。 |

**傳回：**  
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

傳回遍歷集合的列舉器。

**傳回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將整個集合複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列 |
| index | int | 目標陣列中的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回：**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回：**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回：**  
com.aspose.slides.IDOMObject