---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: 組み合わせ可能な系列のグループのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ichartseriesgroupcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

組み合わせ可能な系列のグループのコレクションを表します。

--------------------

1) 各系列グループは、組み合わせ可能な型を持つ系列を含みます。組み合わせ可能な系列型のグループは CombinableSeriesTypesGroup 列挙体で定義および記述されます。また、各系列グループには、一次軸または二次軸のいずれかにプロットされる系列が含まれます（一つのグループ内で両方のケースはありません）。したがって、系列のグループ化の原則は、前述の型グループと一次/二次プロットタイプによるグループ化です。 2) 系列グループは、グループ内の各系列に共通するいくつかの系列プロパティ（「系列グループプロパティ」）を含みます。ChartSeriesGroup クラスの「系列グループプロパティ」は読み取り/書き込み可能です。「系列グループプロパティ」の各項目は、ChartSeries クラスで読み取り専用の投影を持つことができます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Gets the series group by series. |
| [get_Item(int index)](#get-Item-int-) | Gets the series group by index. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

シリーズによって系列グループを取得します。

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

インデックスによって系列グループを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)