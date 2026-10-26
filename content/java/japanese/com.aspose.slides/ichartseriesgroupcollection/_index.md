---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Java API リファレンス
description: 結合可能なシリーズのグループのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ichartseriesgroupcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

結合可能なシリーズのグループのコレクションを表します。

--------------------

1) 各シリーズ グループは、結合可能なタイプのシリーズを含みます。結合可能なシリーズ タイプのグループは CombinableSeriesTypesGroup 列挙型で定義および記述されます。また、各シリーズ グループは、主軸上にプロットされるか副軸上にプロットされるかのシリーズを含みます（同一グループ内で両方の場合はありません）。したがって、シリーズ グループ化の原則は、前述のタイプ グループと主軸/副軸のプロット タイプによるグループ化です。 2) シリーズ グループは、グループ内の各シリーズに共通するいくつかのシリーズ プロパティ（「シリーズ グループ プロパティ」）を含みます。ChartSeriesGroup クラスの「シリーズ グループ プロパティ」は読み書き可能です。「シリーズ グループ プロパティ」のそれぞれは、ChartSeries クラスで読み取り専用のプロジェクションを持つことができます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | シリーズからシリーズ グループを取得します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスでシリーズ グループを取得します。 |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

シリーズからシリーズ グループを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**戻り値:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

インデックスでシリーズ グループを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)