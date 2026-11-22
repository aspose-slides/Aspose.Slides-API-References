---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup クラス

シリーズのグループを表します。

IChartSeriesGroup 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/type/) | このシリーズ グループの型を返します。<br/> 読み取り専用 [`CombinableSeriesTypesGroup`](/slides/python-net/ja/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | このグループのシリーズが二次軸に描画されるかどうかを示します。<br/> 読み取り専用 **bool**. |
| [`series`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/series/) | チャートシリーズの読み取り専用コレクションを返します。<br/> 読み取り専用 [`IChartSeriesReadonlyCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Line- または Stock- チャートの上/下バーへのアクセスを提供します。<br/> 読み取り専用 [`IUpDownBarsManager`](/slides/python-net/ja/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/gap_width/) | 棒または列クラスター間の間隔を、棒または列の幅のパーセンテージとして取得または設定します。<br/> 値は0から500の間でなければなりません。<br/> 読み取り/書き込み **int**. |
| [`gap_depth`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 3D チャートにおけるデータシリーズ間の距離を、マーカー幅のパーセンテージとして取得または設定します。<br/> 値は0から500の間でなければなりません。<br/> 読み取り/書き込み **int**. |
| [`first_slice_angle`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | 最初の円グラフまたはドーナッツ グラフのスライスの角度を取得または設定します。<br/> 度単位（上から時計回りに、0〜360 度）。<br/> 読み取り/書き込み **int**. |
| [`is_color_varied`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | シリーズ内の各データマーカーが異なる色を持つことを指定します。<br/> 読み取り/書き込み **bool**. |
| [`has_series_lines`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | チャートにシリーズ線がある場合は true。スタックバーおよび OfPie チャートに適用されます。<br/> 読み取り/書き込み **bool**. |
| [`overlap`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/overlap/) | 2-D チャートで棒および列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。<br/> - -100%: 最大間隔（棒が完全に分離）。<br/> - 0%: 棒が重なりも間隔もなく並んで配置されます。<br/> - 100%: 最大重なり（棒が完全に重なる）。<br/> このプロパティは読み取り/書き込み **int**. |
| [`second_pie_size`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | pie-of-pie チャートまたは bar-of-pie チャートの 2 番目の円や棒のサイズを、最初の円のサイズのパーセンテージで指定します（5% から 200% の間）。<br/> 読み取り/書き込み **int**. |
| [`pie_split_position`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | pie-of-pie または bar-of-pie チャートで、どのデータポイントが 2 番目の円または棒に属するかを決定するために使用される値を指定します。<br/> PieSplitBy プロパティと共に使用されます。<br/> 読み取り/書き込み **float**. |
| [`pie_split_by`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | pie-of-pie または bar-of-pie チャートで、どのデータポイントが 2 番目の円または棒に属するかを決定する方法を指定します。<br/> 読み取り/書き込み [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | カスタム分割を持つ pie-of-pie または bar-of-pie チャートのカスタム分割情報です。<br/> 2 番目の円または棒に描画されるデータポイントを含みます。<br/> 読み取り専用 [`IPieSplitCustomPointCollection`](/slides/python-net/ja/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | ドーナッツ チャートの穴のサイズを指定します（プロット領域のサイズの 10% から 90% の間）。<br/> 読み取り/書き込み **int**. |
| [`bubble_size_scale`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | バブルチャートのスケール係数を指定します（デフォルトサイズの 0% から 300% の間）。<br/> 読み取り/書き込み **int**. |
| [`hi_low_lines_format`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | HiLowLines の形式を指定します。<br/> HiLowLines は HiLowClose、OpenHiLowClose、VolumeHiLowClose、VolumeOpenHiLowClose チャートタイプで適用されます。 |
| [`bubble_size_representation`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | バブルチャート上でバブルサイズ値がどのように表現されるかを指定します。<br/> 読み取り/書き込み [`BubbleSizeRepresentationType`](/slides/python-net/ja/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

指定されたインデックスの要素を取得します。

## Indexer

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### 備考

1) ChartSeriesGroupCollection クラスおよび CombinableSeriesTypesGroup 列挙体の概要と備考をご覧ください。  
2) シリーズ グループには、グループ内の各シリーズに共通のいくつかのシリーズ プロパティが含まれます（「シリーズ グループ プロパティ」）。ChartSeries クラスの「シリーズ グループ プロパティ」は読み取り/書き込みです。各「シリーズ グループ プロパティ」には、ChartSeries クラスで読み取り専用の投影を持たせることができます。

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)