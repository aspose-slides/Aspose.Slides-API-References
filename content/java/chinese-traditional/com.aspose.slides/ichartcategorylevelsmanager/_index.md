---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: 管理圖表類別層級值的容器。
type: docs
url: /zh-hant/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

管理圖表類別層級值的容器。
## 方法

| Method | 說明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回 IChartDataCell 物件，對於指定的等級。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 設定指定等級的分組項目。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 刪除指定等級的分組項目。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

返回 IChartDataCell 物件，對於指定的等級。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int |  |

**傳回值：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

設定指定等級的分組項目。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int | 類別層級 int |
| value | java.lang.Object | 分組項目 Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

刪除指定等級的分組項目。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int | 類別層級 int |