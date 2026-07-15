---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: 管理圖表類別層級值的容器。
type: docs
url: /zh-hant/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

管理圖表類別層級值的容器。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 傳回為定義層級的 IChartDataCell 物件。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 設定為定義層級的分組項目。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 刪除為定義層級的分組項目。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

傳回為定義層級的 IChartDataCell 物件。

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

設定為定義層級的分組項目。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int | 類別層級 int |
| value | java.lang.Object | 分組項目 物件 |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

刪除為定義層級的分組項目。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int | 類別層級 int |