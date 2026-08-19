---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Kontainer terkelola nilai-nilai level kategori diagram.
type: docs
url: /id/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Kontainer terkelola nilai-nilai level kategori diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Mengembalikan objek IChartDataCell untuk level yang ditentukan. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Menetapkan item pengelompokan untuk level yang ditentukan. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Menghapus item pengelompokan untuk level yang ditentukan. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```


Mengembalikan objek IChartDataCell untuk level yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| level | int |  |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```


Menetapkan item pengelompokan untuk level yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| level | int | Category level int |
| value | java.lang.Object | Groping item Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


Menghapus item pengelompakan untuk level yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| level | int | Category level int |