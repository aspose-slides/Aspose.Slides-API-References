---
title: ShapeCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shapecollection/
---
## ShapeCollection クラス

Represents a collection of shapes.

The ShapeCollection type exposes the following members:

## プロパティ

| Property | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/ja/aspose.slides/shapecollection/parent_group/) | Gets the parent group shape object for the shapes collection.<br/>            Read-only [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |

指定されたインデックスの要素を取得します。  
            読み取り専用 [`IShape`](/slides/python-net/ja/aspose.slides/ishape).

## インデクサ

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/shapecollection/__getitem__/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            シェイプ コレクションの末尾に追加します。 |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/ja/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            シェイプ コレクションの末尾に追加します。 |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/ja/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | 新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/ja/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | 新しい Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | 新しい Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | 事前定義された画像を使用した新しい Zoom フレームを作成し、シェイプ コレクションに<br/>            指定されたインデックスで挿入します。 |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/ja/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | 新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/ja/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | 事前定義された画像を使用した新しい Section Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | 新しい Section Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | 事前定義された画像を使用した新しい Section Zoom フレームを作成し、シェイプ<br/>            コレクションに指定されたインデックスで挿入します。 |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/ja/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/ja/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/ja/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/ja/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ<br/>            コレクションの末尾に追加します。埋め込まれたオーディオは Presentation.Audios コレクションに追加されます。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/ja/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | 既存の Presentation.Audios リストのオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | 埋め込み WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ<br/>            コレクションの指定インデックスに挿入します。埋め込まれたオーディオは Presentation.Audios<br/>            コレクションに追加されます。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | 既存の Presentation.Audios リストのオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`to_array(self)`](/slides/python-net/ja/aspose.slides/shapecollection/to_array/#) | すべてのシェイプを含む配列を作成して返します。 |
| [`to_array(self, start_index, count)`](/slides/python-net/ja/aspose.slides/shapecollection/to_array/#int-int) | 指定された範囲内のすべてのシェイプを含む配列を作成して返します。 |
| [`reorder(self, index, shape)`](/slides/python-net/ja/aspose.slides/shapecollection/reorder/#int-ishape) | 指定されたシェイプをシェイプ コレクション内の新しい位置に移動します。 |
| [`reorder(self, index, shapes)`](/slides/python-net/ja/aspose.slides/shapecollection/reorder/#int-listishape) | 指定されたシェイプをシェイプ コレクション内で移動し、指定されたインデックスから配置します。 |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | デフォルトの書式設定で新しいオートシェイプを作成し、シェイプ<br/>            コレクションの末尾に追加します。 |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | 新しいオートシェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトのテンプレート書式で初期化できます。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。<br/>            デフォルトのテンプレート書式を適用します。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。<br/>            オプションでデフォルトのテンプレートスタイルで初期化できます。 |
| [`add_group_shape(self)`](/slides/python-net/ja/aspose.slides/shapecollection/add_group_shape/#) | 新しい空のグループ シェイプを作成し、シェイプ コレクションの末尾に追加します。<br/>            グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。 |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | 新しいグループ シェイプを作成し、指定された SVG 画像を個別のシェイプに変換し、<br/>            生成されたグループをシェイプ コレクションの末尾に追加します。 |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | デフォルトのテンプレートスタイルで新しいコネクタ シェイプを作成し、シェイプ<br/>            コレクションの末尾に追加します。 |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | 新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。<br/>            オプションでデフォルトのテンプレートスタイルを適用できます。 |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | 新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。<br/>            デフォルトのテンプレートスタイルを適用します。 |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | 新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。<br/>            オプションでデフォルトのテンプレートスタイルを適用できます。 |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/ja/aspose.slides/shapecollection/add_clone/#ishape-float-float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。<br/>            新しいシェイプは `source_shape` の幅と高さを保持します。 |
| [`add_clone(self, source_shape)`](/slides/python-net/ja/aspose.slides/shapecollection/add_clone/#ishape) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。<br/>            クローンされたシェイプは元の位置とサイズを保持します。 |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。<br/>            新しいシェイプは `source_shape` の幅と高さを保持します。 |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_clone/#int-ishape) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。<br/>            クローンされたシェイプは元の位置とサイズを保持します。 |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/ja/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | SmartArt ダイアグラムを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | 新しい Summary Zoom フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | 新しい Summary Zoom フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | 新しいビデオ フレームを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションに<br/>            指定されたインデックスで挿入します。 |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプ<br/>            コレクションの末尾に追加します。 |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプ<br/>            コレクションの指定インデックスに挿入します。 |
| [`index_of(self, shape)`](/slides/python-net/ja/aspose.slides/shapecollection/index_of/#ishape) | コレクション内で指定されたシェイプが最初に出現するゼロベースのインデックスを返します。 |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/ja/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | 数式コンテンツをホストする新しい矩形オートシェイプを作成し、シェイプ コレクションの<br/>            末尾に追加します。 |
| [`insert_group_shape(self, index)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_group_shape/#int) | 新しい空のグループ シェイプを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。<br/>            グループのフレームは、追加されたシェイプに合わせて自動的に調整されます。 |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/ja/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | 指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | 指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの<br/>            指定されたインデックスに挿入します。 |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/ja/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | 新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/ja/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | 新しいテーブルを作成し、指定されたインデックスにシェイプ コレクションへ挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/shapecollection/remove_at/#int) | 指定されたインデックスのシェイプをシェイプ コレクションから削除します。 |
| [`remove(self, shape)`](/slides/python-net/ja/aspose.slides/shapecollection/remove/#ishape) | シェイプ コレクションから指定されたシェイプの最初の出現を削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/shapecollection/clear/#) | シェイプ コレクションからすべてのシェイプを削除します。 |


### 参照
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)