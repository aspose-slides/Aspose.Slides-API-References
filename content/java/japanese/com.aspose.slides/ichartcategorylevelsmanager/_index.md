---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /ja/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

Managed container of the values of the chart category levels.
## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 定義されたレベルの IChartDataCell オブジェクトを返します。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 定義されたレベルのグループ化アイテムを設定します。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 定義されたレベルのグループ化アイテムを削除します。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

定義されたレベルの IChartDataCell オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| level | int |  |

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

定義されたレベルのグループ化アイテムを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| level | int | Category level int |
| value | java.lang.Object | グループ化アイテム オブジェクト |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

定義されたレベルのグループ化アイテムを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| level | int | Category level int |