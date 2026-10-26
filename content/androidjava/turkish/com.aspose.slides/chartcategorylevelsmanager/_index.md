---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides Android için Java API Referansı
description: Grafik kategori seviyelerinin değerlerinin yönetilen konteyneri.
type: docs
url: /tr/com.aspose.slides/chartcategorylevelsmanager/
---
**Kalıtım:**  
java.lang.Object

**Uygulanan Tüm Arayüzler:**  
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)  
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

Grafik kategori seviyelerinin yönetilen konteyneri.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Belirtilen seviye için IChartDataCell nesnesi döndürür. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Belirtilen seviye için gruplama öğesini ayarlar. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Belirtilen seviyedeki gruplama öğesini siler. |

### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

Belirtilen seviye için IChartDataCell nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | int |  |

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

Belirtilen seviye için gruplama öğesini ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

Belirtilen seviyedeki gruplama öğesini siler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | int |  |