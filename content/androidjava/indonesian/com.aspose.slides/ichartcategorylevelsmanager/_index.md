---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Kontainer yang dikelola untuk nilai-nilai tingkat kategori bagan.
type: docs
url: /id/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Kontainer yang dikelola untuk nilai-nilai tingkat kategori bagan.
## Metode

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Mengembalikan objek IChartDataCell untuk level yang ditentukan. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Mengatur item pengelompokan untuk level yang ditentukan. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Menghapus item pengelompokan untuk level yang ditentukan. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Mengembalikan objek IChartDataCell untuk level yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Mengatur item pengelompokan untuk level yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | Level kategori int |
| value | java.lang.Object | Item pengelompokan Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Menghapus item pengelompokan untuk level yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int | Level kategori int |