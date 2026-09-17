---
title: IDataLabel class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabel/
---
## IDataLabel クラス

シリーズ ラベルを表します。

IDataLabel 型は以下のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/idatalabel/is_visible/) | False はデータ ラベルが表示されないことを意味します（そのためすべての Show*-flags (ShowValue, …) が false になります）。<br/>            Read-only **bool**. |
| [`data_label_format`](/slides/python-net/ja/aspose.slides.charts/idatalabel/data_label_format/) | データ ラベルの形式を返します。<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ja/aspose.slides.charts/idatalabel/value_from_cell/) | ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。 |
| [`x`](/slides/python-net/ja/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/ja/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/ja/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/ja/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/ja/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/ja/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/ja/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/ja/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/ja/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/ja/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/ja/aspose.slides.charts/idatalabel/actual_height/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`hide(self)`](/slides/python-net/ja/aspose.slides.charts/idatalabel/hide/#) | すべての Show*-flags (ShowValue, …) を false 状態に設定してデータ ラベルを非表示にします。<br/>            IsVisible はこれにより false になります。 |
| [`get_actual_label_text(self)`](/slides/python-net/ja/aspose.slides.charts/idatalabel/get_actual_label_text/#) | DataLabelFormat 設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ja/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)