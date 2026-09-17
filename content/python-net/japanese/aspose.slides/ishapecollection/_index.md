---
title: IShapeCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishapecollection/
---
## IShapeCollection クラス

シェイプのコレクションを表します。

IShapeCollection 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`parent_group`](/slides/python-net/ja/aspose.slides/ishapecollection/parent_group/) | シェイプ コレクションの親グループ シェイプ オブジェクトを取得します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |

指定されたインデックスの要素を取得します。読み取り専用 [`IShape`](/slides/python-net/ja/aspose.slides/ishape)。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/ishapecollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            シェイプ コレクションの末尾に追加します。 |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            シェイプ コレクションの末尾に追加します。 |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | 新しいチャートを作成し、サンプル系列データと設定で初期化し、<br/>            指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | 新しい OLE オブジェクト フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | 新しい OLE オブジェクト フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | 新しいズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | 新しいズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | 新しいズーム フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | 事前定義された画像を持つ新しいズーム フレームを作成し、シェイプ コレクションに挿入します<br/>            指定されたインデックスで。 |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | 新しいセクション ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | 事前定義された画像を持つ新しいセクション ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | 新しいセクション ズーム フレームを作成し、シェイプ コレクションに指定されたインデックスで挿入します。 |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | 事前定義された画像を持つ新しいセクション ズーム フレームを作成し、シェイプ コレクションに指定されたインデックスで挿入します。 |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | 新しいビデオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | 埋め込まれた WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。<br/>            埋め込まれたオーディオは Presentation.Audios コレクションに追加されます。 |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | 既存の Presentation.Audios リストからオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | 埋め込まれた WAV ファイルを持つ新しいオーディオ フレームを作成し、シェイプ コレクションに<br/>            指定されたインデックスで挿入します。埋め込まれたオーディオは Presentation.Audios<br/>            コレクションに追加されます。 |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | 既存の Presentation.Audios リストからオーディオ オブジェクトを使用して、新しいオーディオ フレームを作成し、シェイプ コレクションの指定されたインデックスに挿入します。 |
| [`to_array(self)`](/slides/python-net/ja/aspose.slides/ishapecollection/to_array/#) | すべてのシェイプを含む配列を作成し、返します。 |
| [`to_array(self, start_index, count)`](/slides/python-net/ja/aspose.slides/ishapecollection/to_array/#int-int) | 指定された範囲のすべてのシェイプを含む配列を作成し、返します。 |
| [`reorder(self, index, shape)`](/slides/python-net/ja/aspose.slides/ishapecollection/reorder/#int-ishape) | 指定されたシェイプをシェイプ コレクション内の新しい位置に移動します。 |
| [`reorder(self, index, shapes)`](/slides/python-net/ja/aspose.slides/ishapecollection/reorder/#int-listishape) | 指定されたシェイプをシェイプ コレクション内で移動し、指定されたインデックスから配置します。 |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | デフォルトの書式設定で新しいオートシェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | 新しいオートシェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトのテンプレート書式設定で初期化します。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。デフォルトのテンプレート書式設定を適用します。 |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | 新しいオートシェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。オプションでデフォルトのテンプレートスタイリングで初期化します。 |
| [`add_group_shape(self)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_group_shape/#) | 新しい空のグループ シェイプを作成し、シェイプ コレクションの末尾に追加します。<br/>            グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | 新しいグループ シェイプを作成し、指定された SVG 画像を個々のシェイプに変換し、生成されたグループをシェイプ コレクションの末尾に追加します。 |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | デフォルトのテンプレートスタイリングで新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | 新しいコネクタ シェイプを作成し、シェイプ コレクションの末尾に追加します。オプションでデフォルトのテンプレートスタイリングを適用します。 |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | 新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。デフォルトのテンプレートスタイリングを適用します。 |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | 新しいコネクタ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。オプションでデフォルトのテンプレートスタイリングを適用します。 |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。<br/>            新しいシェイプは `source_shape` の幅と高さを保持します。 |
| [`add_clone(self, source_shape)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_clone/#ishape) | 指定されたシェイプのコピーを作成し、シェイプ コレクションの末尾に追加します。<br/>            コピーされたシェイプは元の位置とサイズを保持します。 |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。<br/>            新しいシェイプは `source_shape` の幅と高さを保持します。 |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_clone/#int-ishape) | 指定されたシェイプのコピーを作成し、指定されたインデックスにシェイプ コレクションに挿入します。<br/>            コピーされたシェイプは元の位置とサイズを保持します。 |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | SmartArt 図を作成し、シェイプ コレクションの末尾に追加します。 |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | 新しいサマリー ズーム フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | 新しいサマリー ズーム フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | 新しいビデオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | CD トラックにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | CD トラックにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | 外部オーディオ ファイルにリンクされた新しいオーディオ フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`index_of(self, shape)`](/slides/python-net/ja/aspose.slides/ishapecollection/index_of/#ishape) | コレクション内で指定されたシェイプが最初に出現するゼロベースのインデックスを返します。 |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | 数式コンテンツをホストするための新しい矩形オートシェイプを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_group_shape(self, index)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_group_shape/#int) | 新しい空のグループ シェイプを作成し、指定されたインデックスにシェイプ コレクションに挿入します。<br/>            グループのフレームは追加されたシェイプに合わせて自動的に調整されます。 |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | 指定された画像を含む新しい画像フレームを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | 指定された画像を含む新しい画像フレームを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/ja/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | 新しいテーブルを作成し、シェイプ コレクションの末尾に追加します。 |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/ja/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | 新しいテーブルを作成し、指定されたインデックスにシェイプ コレクションに挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/ishapecollection/remove_at/#int) | シェイプ コレクションから指定されたインデックスのシェイプを削除します。 |
| [`remove(self, shape)`](/slides/python-net/ja/aspose.slides/ishapecollection/remove/#ishape) | シェイプ コレクションから指定されたシェイプの最初の出現を削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/ishapecollection/clear/#) | シェイプ コレクションからすべてのシェイプを削除します。 |


### 参照
* クラス [`IShape`](/slides/python-net/ja/aspose.slides/ishape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)