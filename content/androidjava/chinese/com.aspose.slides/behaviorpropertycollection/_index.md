---
title: BehaviorPropertyCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示效果行为的计时属性。
type: docs
url: /zh/com.aspose.slides/behaviorpropertycollection/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

表示效果行为的计时属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中存储的属性数量。 |
| [isReadOnly()](#isReadOnly--) | 获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。 |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | 向集合中添加一个新属性。 |
| [add(String propertyValue)](#add-java.lang.String-) | 向集合中添加一个新属性。 |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | 确定列表中特定项的索引。 |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | 通过属性值确定列表中特定项的索引。 |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | 在指定索引处向集合中插入一个新属性。 |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 在指定索引处向集合中插入一个新属性（使用指定的属性值）。 |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | 将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组，从特定的数组索引开始。 |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | 从集合中移除指定的属性。 |
| [remove(String propertyValue)](#remove-java.lang.String-) | 从集合中移除指定的属性。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引处移除属性。 |
| [clear()](#clear--) | 从集合中移除所有属性。 |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [contains(String propertyValue)](#contains-java.lang.String-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的属性。 |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | 在指定索引处设置属性。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 Java 迭代器。 |

### size() {#size--}
```
public final int size()
```

返回集合中存储的属性数量。只读 int。

**返回：**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

获取一个值，指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否为只读。只读 boolean。

**返回：**
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 为只读则为 true；否则为 false。

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

向集合中添加一个新属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要添加的属性。 |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

向集合中添加一个新属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要添加的属性值。 |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

确定列表中特定项的索引。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要在列表中定位的对象。 |

**返回：**
int - 如果在列表中找到项，则返回其索引；否则返回 -1。

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

通过属性值确定列表中特定项的索引。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 属性的值 |

**返回：**
int - 具有指定值的属性的索引

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

在指定索引处向集合中插入一个新属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 应插入新属性的索引。 |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要添加的属性。 |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

在指定索引处向集合中插入一个新属性（使用指定的属性值）。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 应插入新属性的索引。 |
| propertyValue | java.lang.String | 要添加的属性值。 |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

将 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素复制到数组，从特定的数组索引开始。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | 目标是一维数组，接收从 [IGenericCollection](../../com.aspose.slides/igenericcollection) 复制来的元素。数组必须使用零基索引。 |
| arrayIndex | int | 复制开始的数组零基索引。 |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

从集合中移除指定属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要移除的属性。 |

**返回：**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

从集合中移除指定属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要移除的属性值。 |

**返回：**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定索引处移除属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 应删除的属性的索引。 |

### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有属性。

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的属性。 |

**返回：**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到项则返回 true；否则返回 false。

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的属性值。 |

**返回：**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 propertyValue 则返回 true；否则返回 false。

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

返回指定索引处的属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 要返回的属性的索引。 |

**返回：**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - 动画行为属性。

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

在指定索引处设置属性。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 要设置的属性的索引。 |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - 可用于遍历集合的 IGenericEnumerator。

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**返回：**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**返回：**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**返回：**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

返回整个集合的 Java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - 一个用于整个集合的 java.util.Iterator。