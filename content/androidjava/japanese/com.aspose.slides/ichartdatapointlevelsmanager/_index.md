---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: データ ポイント レベルのコンテナです。
type: docs
url: /ja/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

データ ポイント レベルのコンテナです。Treeamp および Sunburst 系列に適用されます。データ ポイント レベルのインデックスは 0 から始まります。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 定義されたレベルの IChartDataPointLevel オブジェクトを返します。 |
| [getCount()](#getCount--) | データ ポイント レベルの数を返します。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


定義されたレベルの IChartDataPointLevel オブジェクトを返します。

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


データ ポイント レベルの数を返します。

**戻り値:**
int