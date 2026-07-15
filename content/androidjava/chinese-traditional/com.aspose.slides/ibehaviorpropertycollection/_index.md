---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示效果行為的時間屬性。
type: docs
url: /zh-hant/com.aspose.slides/ibehaviorpropertycollection/
---
**所有已實作的介面:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

表示效果行為的時間屬性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | 將新屬性新增到集合中。 |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | 根據屬性值在 List 中確定特定項目的索引。 |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 在指定索引處將新屬性（具有指定的屬性值）插入集合。 |
| [remove(String propertyValue)](#remove-java.lang.String-) | 從集合中移除指定的屬性。 |
| [contains(String propertyValue)](#contains-java.lang.String-) | 確定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

將新屬性新增到集合中。

**參數:** 
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要新增的屬性值。 |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

根據屬性值在 List 中確定特定項目的索引。

**參數:** 
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 屬性值 |

**返回:** 
int - 具有指定值的屬性的索引
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

在指定索引處將新屬性（具有指定的屬性值）插入集合。

**參數:** 
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 應插入新屬性的索引。 |
| propertyValue | java.lang.String | 要新增的屬性值。 |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

從集合中移除指定的屬性。

**參數:** 
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要移除的屬性值。 |

**返回:** 
boolean - 若成功移除屬性則返回 true boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

確定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數:** 
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的屬性值。 |

**返回:** 
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 propertyValue 則返回 true；否則返回 false.