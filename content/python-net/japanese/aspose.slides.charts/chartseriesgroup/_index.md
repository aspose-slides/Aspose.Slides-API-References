---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup クラス

シリーズのグループを表します。

ChartSeriesGroup 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/type/) | このシリーズ グループの型を返します。<br/>            読み取り専用 [`CombinableSeriesTypesGroup`](/slides/python-net/ja/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | このグループのシリーズが二次軸にプロットされるかどうかを示します。<br/>            読み取り専用 **bool**. |
| [`series`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/series/) | シリーズのコレクションを返します。<br/>            読み取り専用 [`IChartSeriesReadonlyCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Line- または Stock-チャートの上下バーへのアクセスを提供します。<br/>            読み取り専用 [`IUpDownBarsManager`](/slides/python-net/ja/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/gap_width/) | バーまたは列クラスター間のスペースを、バーまたは列の幅のパーセンテージとして取得または設定します。<br/>            値は 0 から 500 の間である必要があります。<br/>            読み書き **int**. |
| [`gap_depth`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/gap_depth/) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージとして取得または設定します。<br/>            値は 0 から 500 の間である必要があります。<br/>            読み書き **int**. |
| [`first_slice_angle`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | 最初の円またはドーナツチャートのスライスの角度を取得または設定します、<br/>            度単位（上から時計回り、0 から 360 度）。<br/>            読み書き **int**. |
| [`doughnut_hole_size`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 0% から 90% の間）。<br/>            読み書き **int**. |
| [`overlap`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/overlap/) | 2D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。<br/>             - -100%: 最大間隔（バーは完全に分離）。<br/>             - 0%: バーは重なりや間隔なしで隣り合って配置。<br/>             - 100%: 最大重なり（バーは互いに完全に重なる）。<br/>             このプロパティは読み書き **int**. |
| [`second_pie_size`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/second_pie_size/) | 円の中の円チャートまたは円の中の棒チャートにおける第2の円または棒のサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の間）。<br/>            読み書き **int**. |
| [`bubble_size_representation`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。<br/>            読み書き [`BubbleSizeRepresentationType`](/slides/python-net/ja/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/pie_split_position/) | 円の中の円チャートまたは円の中の棒チャートにおいて、どのデータ点が第2の円または棒に含まれるかを決定するために使用される値を指定します。<br/>            PieSplitBy プロパティと併用します。<br/>            読み書き **float**. |
| [`pie_split_by`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/pie_split_by/) | 円の中の円チャートまたは円の中の棒チャートで、どのデータ点が第2の円または棒に含まれるかを決定する方法を指定します。<br/>            読み書き [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/is_color_varied/) | 系列内の各データマーカーに異なる色が付くように指定します。<br/>            読み書き **bool**. |
| [`has_series_lines`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/has_series_lines/) | チャートに系列線がある場合は true。積み上げ棒グラフおよび OfPie グラフに適用されます。<br/>            読み書き **bool**. |
| [`hi_low_lines_format`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | HiLowLines の形式を指定します。<br/>            HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャートタイプで適用されます。 |
| [`bubble_size_scale`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の間）。<br/>            読み書き **int**. |
| [`pie_split_custom_points`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | カスタム分割を持つ円の中の円チャートまたは円の中の棒チャートのカスタム分割情報。<br/>            円の中の円または円の中の棒チャートで第2の円または棒に描画されるデータ点を含みます。<br/>            読み取り専用 [`PieSplitCustomPointCollection`](/slides/python-net/ja/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/presentation/) |  |

指定したインデックスの要素を取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### 備考

1) ChartSeriesGroupCollection クラス と CombinableSeriesTypesGroup 列挙型 の概要と備考をご覧ください。  
2) 系列のグループには、グループ内の各系列に共通するいくつかの系列プロパティが含まれます（「シリーズ グループ プロパティ」）。  
「シリーズ グループ プロパティ」は ChartSeriesGroup クラスで読み書き可能です。  
「シリーズ グループ プロパティ」の各項目は、ChartSeries クラスで読み取り専用の投影を持つことができます。

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)