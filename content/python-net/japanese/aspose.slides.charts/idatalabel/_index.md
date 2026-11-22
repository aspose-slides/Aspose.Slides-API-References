---
title: IDataLabel class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabel/
---
## IDataLabel クラス

シリーズラベルを表します。

IDataLabel 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/idatalabel/is_visible/) | False はデータ ラベルが表示されないことを意味します (そのためすべての Show*-フラグ (ShowValue, ...) は false になります)。<br/>            読み取り専用 **bool**. |
| [`data_label_format`](/slides/python-net/ja/aspose.slides.charts/idatalabel/data_label_format/) | データ ラベルの形式を返します。<br/>            読み取り専用 [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ja/aspose.slides.charts/idatalabel/value_from_cell/) | ワークブック データ セルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。 |
| [`label_shape_type`](/slides/python-net/ja/aspose.slides.charts/idatalabel/label_shape_type/) | データ ラベルのシェイプ タイプを取得または設定します。<br/>            シェイプが定義されていない場合は [`ShapeType.NOT_DEFINED`](/slides/python-net/ja/aspose.slides/shapetype/NOT_DEFINED) を返します。 |
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

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/ja/aspose.slides.charts/idatalabel/hide/#) | すべての Show*-フラグ (ShowValue, ...) を false に設定してデータ ラベルを非表示にします。<br/>            この操作後、IsVisible は false になります。 |
| [`get_actual_label_text(self)`](/slides/python-net/ja/aspose.slides.charts/idatalabel/get_actual_label_text/#) | DataLabelFormat の設定または TextFrameForOverriding.Text の値に基づいて実際のラベル テキストを返します。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ja/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)