---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup クラス

シリーズのグループを表します。

IChartSeriesGroup 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/type/) | このシリーズグループの型を返します。<br/>            読み取り専用 [`CombinableSeriesTypesGroup`](/slides/python-net/ja/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | このグループのシリーズが二次軸にプロットされているかどうかを示します。<br/>            読み取り専用 **bool**. |
| [`series`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/series/) | チャートシリーズの読み取り専用コレクションを返します。<br/>            読み取り専用 [`IChartSeriesReadonlyCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Line- または Stock-チャートの上/下バーへのアクセスを提供します。<br/>            読み取り専用 [`IUpDownBarsManager`](/slides/python-net/ja/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/gap_width/) | バーまたは列クラスタ間のスペースを、バーまたは列の幅のパーセンテージで指定します。<br/>            読み書き可能 **int**. |
| [`gap_depth`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。<br/>            読み書き可能 **int**. |
| [`first_slice_angle`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | 最初の円グラフまたはドーナツグラフのスライスの角度を取得または設定します、<br/>            度単位（上から時計回りに、0 から 360 度）。<br/>            読み書き可能 **int**. |
| [`is_color_varied`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | 系列内の各データマーカーが異なる色を持つことを指定します。<br/>            読み書き可能 **bool**. |
| [`has_series_lines`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | チャートに系列線がある場合は true。スタックバーと OfPie チャートに適用されます。<br/>            読み書き可能 **bool**. |
| [`overlap`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/overlap/) | 2-D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。<br/>             - -100%: 最大間隔（バーは完全に分離）。<br/>             - 0%: バーは重なりや間隔なしで並んで配置されます。<br/>             - 100%: 最大重なり（バーは互いに完全に重なる）。<br/>             このプロパティは読み書き可能 **int**. |
| [`second_pie_size`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | pie-of-pie チャートまたは bar-of-pie チャートの第 2 の円またはバーのサイズを、第 1 の円のサイズのパーセンテージで指定します（5% から 200% の間で指定可能）。<br/>            読み書き可能 **int**. |
| [`pie_split_position`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | pie-of-pie または bar-of-pie チャートで第 2 の円またはバーに含めるデータポイントを決定するために使用される値を指定します。<br/>            PieSplitBy プロパティと併せて使用されます。<br/>            読み書き可能 **float**. |
| [`pie_split_by`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | pie-of-pie または bar-of-pie チャートで第 2 の円またはバーに含めるデータポイントを決定する方法を指定します。<br/>            読み書き可能 [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | カスタム分割を持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。<br/>            pie-of-pie または bar-of-pie チャートの第 2 の円またはバーに描画されるデータポイントを含みます。<br/>            読み取り専用 [`IPieSplitCustomPointCollection`](/slides/python-net/ja/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | ドーナツチャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の間）。<br/>            読み書き可能 **int**. |
| [`bubble_size_scale`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の間）。<br/>            読み書き可能 **int**. |
| [`hi_low_lines_format`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | HiLowLines のフォーマットを指定します。<br/>            HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャートタイプで適用されます。 |
| [`bubble_size_representation`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | バブルチャート上でバブルサイズ値がどのように表現されるかを指定します。<br/>            読み書き可能 [`BubbleSizeRepresentationType`](/slides/python-net/ja/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

指定されたインデックスの要素を取得します。

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### 備考

1) ChartSeriesGroupCollection クラスおよび CombinableSeriesTypesGroup 列挙体の概要と備考を参照してください。  
2) シリーズのグループには、グループ内の各シリーズに共通のいくつかのシリーズプロパティ（「シリーズ グループ プロパティ」）が含まれています。  
ChartSeriesGroup クラスの「Series group properties」は読み書き可能です。  
各 "series group properties" は ChartSeries クラスで読み取り専用の投影を持つことができます。

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)