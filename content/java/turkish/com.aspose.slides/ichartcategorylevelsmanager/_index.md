---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Grafik kategori seviyelerinin değerlerinin yönetilen konteyneri.
type: docs
url: /tr/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Grafik kategori seviyelerinin değerlerinin yönetilen konteyneri.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Belirtilen seviye için IChartDataCell nesnesini döndürür. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Belirtilen seviye için gruplama öğesini ayarlar. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Belirtilen seviye için gruplama öğesini siler. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Belirtilen seviye için IChartDataCell nesnesini döndürür.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Belirtilen seviye için gruplama öğesini ayarlar.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | Kategori seviyesi int |
| value | java.lang.Object | Gruplama öğesi Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Belirtilen seviye için gruplama öğesini siler.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | Kategori seviyesi int |