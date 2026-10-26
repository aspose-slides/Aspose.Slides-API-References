---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 受管理的圖表類別層級值容器。
type: docs
url: /zh-hant/com.aspose.slides/chartcategorylevelsmanager/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)  
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

圖表類別層級值的受管理容器。

## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 傳回為定義層級的 IChartDataCell 物件。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 設定為定義層級的分組項目。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 刪除為定義層級的分組項目。 |

### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

傳回為定義層級的 IChartDataCell 物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int |  |

**傳回:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

設定為定義層級的分組項目。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

刪除為定義層級的分組項目。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int |  |