---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /ja/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

チャートカテゴリレベルの値の管理コンテナです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 定義されたレベルの IChartDataCell オブジェクトを返します。 |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 定義されたレベルのグルーピング項目を設定します。 |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 定義されたレベルのグルーピング項目を削除します。 |
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

定義されたレベルのグルーピング項目を設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| level | int | Category level int |
| value | java.lang.Object | グルーピング項目 Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

定義されたレベルのグルーピング項目を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| level | int | Category level int |