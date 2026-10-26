---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Referansı
description: Grafik kategori seviyelerinin değerlerinin yönetilen kapsayıcısı.
type: docs
url: /tr/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Grafik kategori seviyelerinin değerlerinin yönetilen kapsayıcısı.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataCell object for defined level. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Sets grouping item for defined level. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Delete grouping item for defined level. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

Belirtilen seviye için IChartDataCell nesnesini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | int |  |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

Belirtilen seviye için gruplaştırma öğesini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | int | Kategori seviyesi int |
| value | java.lang.Object | Gruplama öğesi Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

Belirtilen seviye için gruplaştırma öğesini siler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | int | Kategori seviyesi int |