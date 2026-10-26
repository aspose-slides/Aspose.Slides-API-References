---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Container of data point levels.
type: docs
url: /ja/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

データポイントレベルのコンテナです。Treeamp および Sunburst 系列に適用されます。データポイントレベルのインデックスは 0 ベースです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 指定されたレベルの IChartDataPointLevel オブジェクトを返します。 |
| [getCount()](#getCount--) | データポイントレベルの数を返します。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


指定されたレベルの IChartDataPointLevel オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| level | int |  |

**戻り値:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


データポイントレベルの数を返します。

**戻り値:**
int