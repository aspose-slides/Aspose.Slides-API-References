---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides for Java API 參考
description: 表示效果行為的時間屬性。
type: docs
url: /zh-hant/com.aspose.slides/ibehaviorpropertycollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

表示效果行為的時間屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | 將新的屬性新增至集合中。 |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | 依屬性值判斷 List 中特定項目的索引。 |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 在指定索引處將新的屬性（具有指定的屬性值）插入至集合中。 |
| [remove(String propertyValue)](#remove-java.lang.String-) | 從集合中移除指定的屬性。 |
| [contains(String propertyValue)](#contains-java.lang.String-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

將新的屬性新增至集合中。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要新增之屬性的值。 |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

依屬性值判斷 List 中特定項目的索引。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 屬性值 |

**回傳值：**
int - 具有指定值的屬性的索引
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

在指定索引處將新的屬性（具有指定的屬性值）插入至集合中。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入新屬性的索引位置。 |
| propertyValue | java.lang.String | 要新增之屬性的值。 |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

從集合中移除指定的屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要移除之屬性的值。 |

**回傳值：**
boolean - 若成功移除屬性則返回 True
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的屬性值。 |

**回傳值：**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 propertyValue 則返回 true；否則返回 false。