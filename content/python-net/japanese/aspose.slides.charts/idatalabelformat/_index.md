---
title: IDataLabelFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat クラス

DataLabel の書式オプションを表します。

IDataLabelFormat 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/) | 読み書き **bool**。 |
| [`number_format`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/number_format/) | DataLabels オブジェクトの書式文字列を表します。<br/>            読み書き **str**。 |
| [`format`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/format/) | データラベルの書式を表します。<br/>            読み取り専用 [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat)。 |
| [`position`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/position/) | データラベルの位置を表します。<br/>            読み書き [`LegendDataLabelPosition`](/slides/python-net/ja/aspose.slides.charts/legenddatalabelposition)。 |
| [`show_legend_key`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_legend_key/) | 特定のチャートのデータラベル凡例キーの表示動作を表します。 <br/>            True if the data label legend key is visible.<br/>            読み書き **bool**。 |
| [`show_value`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_value/) | 特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。 <br/>            True はパーセンテージ値を表示します。False は非表示にします。<br/>            読み書き **bool**。 |
| [`show_category_name`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_category_name/) | 特定のチャートのデータラベルのカテゴリ名の表示動作を表します。<br/>            True はチャート上のデータラベルのカテゴリ名を表示します。False は非表示にします。<br/>            読み書き **bool**。 |
| [`show_series_name`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_series_name/) | チャート上のデータラベルのシリーズ名の表示動作を示す Boolean を取得または設定します。 <br/>            True はシリーズ名を表示します。False は非表示にします。<br/>            読み書き **bool**。 |
| [`show_percentage`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_percentage/) | 特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。 <br/>            True はパーセンテージ値を表示します。False は非表示にします。<br/>            読み書き **bool**。 |
| [`show_bubble_size`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_bubble_size/) | 特定のチャートのデータラベルのバブルサイズ値の表示動作を表します。 <br/>            True はバブルサイズ値を表示します。False は非表示にします。<br/>            読み書き **bool**。 |
| [`show_leader_lines`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_leader_lines/) | 特定のチャートのデータラベルのリーダーラインの表示動作を表します。 <br/>            True はリーダーラインを表示します。False は非表示にします。<br/>            読み書き **bool**。 |
| [`show_label_as_data_callout`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/) | 指定されたチャートのデータラベルがデータコールアウトとして表示されるか、データラベルとして表示されるかを決定します。<br/>            <br/>            この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection コレクション内の新しいデータラベルに対する ShowLabelAsDataCallout プロパティの既定値を取得または設定します。<br/>            このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの ShowLabelAsDataCallout プロパティにも同じ値が設定されます。<br/>            （例: "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" と設定すると、すべての DataLabels[i].ShowLabelAsDataCallout が val と等しくなります。） |
| [`show_label_value_from_cell`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/) | 特定のチャートのデータラベルのセル値の表示動作を表します。 <br/>            True はセル値を表示します。False は非表示にします。<br/>            読み書き **bool**。 |
| [`separator`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/separator/) | チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。<br/>            読み書き **str**。 |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/text_format/) |  |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat/presentation/) |  |

### 関連項目
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)