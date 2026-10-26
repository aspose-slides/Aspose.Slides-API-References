---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示效果行为的计时属性。
type: docs
url: /zh/com.aspose.slides/ibehaviorpropertycollection/
---
**所有已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

表示效果行为的计时属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | 向集合添加新属性。 |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | 通过属性值确定列表中特定项的索引。 |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 在指定索引处向集合插入新属性（使用指定的属性值）。 |
| [remove(String propertyValue)](#remove-java.lang.String-) | 从集合中移除指定属性。 |
| [contains(String propertyValue)](#contains-java.lang.String-) | 确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |

### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

向集合添加新属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要添加的属性值。 |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

通过属性值确定列表中特定项的索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 属性值 |

**返回值：**
int - 具有指定值的属性的索引

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

在指定索引处向集合插入新属性（使用指定的属性值）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 新属性应插入的索引。 |
| propertyValue | java.lang.String | 要添加的属性值。 |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

从集合中移除指定属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要移除的属性值。 |

**返回值：**
boolean - True if a property removed successfully boolean

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

确定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的属性值。 |

**返回值：**
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 propertyValue，则为 true；否则为 false。