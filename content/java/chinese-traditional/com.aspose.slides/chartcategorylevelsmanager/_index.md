---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides for Java API 參考
description: 受管理的容器，用於圖表分類層級的值。
type: docs
url: /zh-hant/com.aspose.slides/chartcategorylevelsmanager/
---
**繼承:**  
java.lang.Object

**全部已實作的介面:**  
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)  
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

受管理的容器，用於圖表分類層級的值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 傳回已定義層級的 IChartDataCell 物件。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 設定已定義層級的分組項目。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 刪除已定義層級的分組項目。 |

### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

傳回已定義層級的 IChartDataCell 物件。

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

設定已定義層級的分組項目。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

刪除已定義層級的分組項目。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int |  |