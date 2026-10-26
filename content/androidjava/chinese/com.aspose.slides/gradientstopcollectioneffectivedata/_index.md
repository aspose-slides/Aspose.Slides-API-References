---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 GradientStopData 对象的集合。
type: docs
url: /zh/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)  
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

表示 GradientStopData 对象的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中梯度停止点的数量。 |
| [get_Item(int index)](#get-Item-int-) | 按索引返回梯度停止点。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 为整个集合返回一个 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示对集合的访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |

### size() {#size--}
```
public final int size()
```

返回集合中梯度停止点的数量。只读 int。

**返回：**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

按索引返回梯度停止点。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**  
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

返回遍历集合的枚举器。

**返回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

为整个集合返回一个 java 迭代器。

**返回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - 整个集合的 java.util.Iterator。

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

返回指示对集合的访问是否同步（线程安全）的值。只读 boolean。

**返回：**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回：**  
java.lang.Object