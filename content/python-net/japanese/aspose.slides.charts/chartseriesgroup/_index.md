---
title: ChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup クラス

シリーズのグループを表します。

ChartSeriesGroup タイプは次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/type/) | このシリーズ グループの型を返します。<br/>            読み取り専用 [`CombinableSeriesTypesGroup`](/slides/python-net/ja/aspose.slides.charts/combinableseriestypesgroup)。 |
| [`plot_on_second_axis`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | このグループのシリーズが二次軸にプロットされるかどうかを示します。<br/>            読み取り専用 **bool**。 |
| [`series`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/series/) | シリーズのコレクションを返します。<br/>            読み取り専用 [`IChartSeriesReadonlyCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesreadonlycollection)。 |
| [`up_down_bars`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Line-またはStock-チャートの上/下バーへのアクセスを提供します。<br/>            読み取り専用 [`IUpDownBarsManager`](/slides/python-net/ja/aspose.slides.charts/iupdownbarsmanager)。 |
| [`gap_width`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/gap_width/) | バーまたは列クラスタ間のスペースを、バーまたは列幅のパーセンテージで指定します。<br/>            読み書き可能 **int**。 |
| [`gap_depth`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/gap_depth/) | 3D チャートのデータ系列間の距離を、マーカー幅のパーセンテージで取得または設定します。<br/>            読み書き可能 **int**。 |
| [`first_slice_angle`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | 最初の円グラフまたはドーナツ グラフのスライスの角度を取得または設定します、<br/>            度単位（上から時計回りに、0 から 360 度）。<br/>            読み書き可能 **int**。 |
| [`doughnut_hole_size`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | ドーナツ グラフの穴のサイズを指定します（プロット領域のサイズの 0% から 90% の間で指定可能）。<br/>            読み書き可能 **int**。 |
| [`overlap`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/overlap/) | 2-D チャートでバーと列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。<br/>             - -100%: 最大間隔（バーは完全に分離）。<br/>             - 0%: バーは重なりや間隔なしで横に並びます。<br/>             - 100%: 最大重なり（バーは完全に重なる）。<br/>             このプロパティは読み書き可能 **int**。 |
| [`second_pie_size`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/second_pie_size/) | pie-of-pie チャートまたは bar-of-pie チャートの第2の円またはバーのサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の間で指定可能）。<br/>            読み書き可能 **int**。 |
| [`bubble_size_representation`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | バブル チャートでバブルサイズの値がどのように表現されるかを指定します。<br/>            読み書き可能 [`BubbleSizeRepresentationType`](/slides/python-net/ja/aspose.slides.charts/bubblesizerepresentationtype)。 |
| [`pie_split_position`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/pie_split_position/) | pie-of-pie または bar-of-pie チャートで第2の円またはバーに含めるデータ点を決定するために使用される値を指定します。<br/>            PieSplitBy プロパティと併せて使用されます。<br/>            読み書き可能 **float**。 |
| [`pie_split_by`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/pie_split_by/) | pie-of-pie または bar-of-pie チャートで第2の円またはバーに含めるデータ点をどのように決定するかを指定します。<br/>            読み書き可能 [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype)。 |
| [`is_color_varied`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/is_color_varied/) | シリーズ内の各データ マーカーが異なる色を持つことを指定します。<br/>            読み書き可能 **bool**。 |
| [`has_series_lines`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/has_series_lines/) | チャートにシリーズラインがある場合は true。スタック バーおよび OfPie チャートに適用されます。<br/>            読み書き可能 **bool**。 |
| [`hi_low_lines_format`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | HiLowLines 形式を指定します。<br/>            HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャート タイプで適用されます。 |
| [`bubble_size_scale`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | バブル チャートのスケール係数を指定します（デフォルト サイズの 0% から 300% の間で指定可能）。<br/>            読み書き可能 **int**。 |
| [`pie_split_custom_points`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | カスタム スプリットを持つ pie-of-pie または bar-of-pie チャートのカスタム スプリット情報。<br/>            pie-of-pie または bar-of-pie チャートの第2の円またはバーに描画されるデータ点を含みます。<br/>            読み取り専用 [`PieSplitCustomPointCollection`](/slides/python-net/ja/aspose.slides.charts/piesplitcustompointcollection)。 |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。 |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/presentation/) |  |

指定されたインデックスの要素を取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### 備考

1) ChartSeriesGroupCollection クラスと CombinableSeriesTypesGroup 列挙体の概要および備考を参照してください。  
2) シリーズのグループには、グループ内の各シリーズに共通するいくつかのシリーズ プロパティが含まれます（「series group properties」）。  
「Series group properties」は ChartSeriesGroup クラスで読み書き可能です。  
「series group properties」の各項目は、ChartSeries クラスで読み取り専用の投影を持つことができます。  

### 関連項目
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)