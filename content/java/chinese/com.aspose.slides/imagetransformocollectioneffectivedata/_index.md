---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides for Java API 参考
description: 不可变对象，表示有效图像变换效果的只读集合。
type: docs
url: /zh/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**继承:**
java.lang.Object

**所有实现的接口:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

不可变对象，表示有效图像变换效果的只读集合。

--------------------

名称 IImageTransformOperationCollectionEffectiveData 被截断为 IImageTransformOCollectionEffectiveData，因为 COM 名称长度不能超过 39。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | Returns the number of image effects in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns element by index. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection into the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


返回集合中图像效果的数量。只读 int.

**返回:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


返回按索引的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) 对象。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的对象是否等于当前对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与当前对象比较的对象。 |

**返回:**
boolean - 如果指定的对象等于当前对象则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


作为特定类型的哈希函数，适用于哈希算法和诸如哈希表的数据结构。

**返回:**
int - 当前对象的哈希码。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


返回一个枚举器，用于遍历集合。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - 用于整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


将集合中的所有元素复制到指定的数组中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要填充的数组。 |
| index | int | 目标数组中的起始位置。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean。

**返回:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


返回同步根。只读 Object。

**返回:**
java.lang.Object