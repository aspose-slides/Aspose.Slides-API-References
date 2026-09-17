---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection クラス

結合可能な系列のグループのコレクションを表します。

IChartSeriesGroupCollection タイプは次のメンバーを公開します。

インデックスで系列グループを取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### 備考

1) 各系列グループは結合可能な型の系列を含みます。結合可能な系列型のグループは **CombinableSeriesTypesGroup** enum で定義および記述されています。また、各系列グループは一次軸または二次軸のいずれかにプロットされる系列を含みます（同一グループ内で両方にプロットされることはありません）。したがって、系列のグループ化の原則は、上記の型グループと一次/二次プロットタイプによるグループ化です。

2) 系列グループは、グループ内の各系列に共通するいくつかの系列プロパティ（「**Series group properties**」）を含みます。「**Series group properties**」は **ChartSeriesGroup** クラスで読み取り/書き込み可能です。各「**Series group properties**」は **ChartSeries** クラスで読み取り専用の投影を持つことができます。

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)