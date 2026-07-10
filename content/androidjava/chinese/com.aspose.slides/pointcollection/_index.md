---
title: PointCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画点的集合。
type: docs
url: /zh/com.aspose.slides/pointcollection/
---
**继承：**
java.lang.Object

**实现的所有接口：**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

表示动画点集合。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中点的数量。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的点。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 Java 迭代器。 |

### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中点的数量。只读 int。

**返回：**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

返回指定索引处的点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[IPoint](../../com.aspose.slides/ipoint) - 该 [IPoint](../../com.aspose.slides/ipoint) 对象。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

返回整个集合的 Java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - 一个 java.util.Iterator 用于整个集合。