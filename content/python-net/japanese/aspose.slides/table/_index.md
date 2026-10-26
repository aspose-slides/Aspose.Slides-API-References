---
title: Table class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/table/
---
## Table クラス

スライド上のテーブルを表します。

**Inheritance:**[`Table`](/slides/python-net/ja/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

The Table type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/table/is_text_holder/) | シェイプが TextHolder_PPT かどうかを決定します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/table/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/table/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/table/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み取り/書き込み [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/table/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み取り/書き込み [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/table/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/table/three_d_format/) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/table/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/table/fill_format/) | Table の塗りつぶし書式を含む TableFormat.FillFormat オブジェクトを返します。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/table/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み取り/書き込み [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/table/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み取り/書き込み [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/table/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/table/hidden/) | シェイプが非表示かどうかを決定します。<br/>            読み取り/書き込み **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/table/z_order_position/) | シェイプの Z オーダーにおける位置を返します。<br/>            Shapes[0] は Z オーダーの後ろ側のシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は前側のシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/table/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/table/rotation/) | 指定されたシェイプが Z 軸周りに回転している角度（度数）を取得または設定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。<br/>            読み取り/書き込み **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/table/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/table/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/table/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/table/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み取り/書き込み **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/table/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み取り/書き込み [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/table/unique_id/) | アドインや他のコードが使用することを目的とした、プレゼンテーション内でスコープされた内部識別子を返します。<br/>            この値はユーザーやプログラムにより再割り当て可能であるため、永続的なユニークキーとして扱ってはなりません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/table/office_interop_shape_id/) | シェイプの存続期間中一定で、PowerPoint やインターオップコードが文書内のどこからでもシェイプを確実に参照できるスライドスコープのユニーク識別子を返します。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/table/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/table/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/table/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み取り/書き込み **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/table/is_decorative/) | 装飾としてマークするオプションを取得または設定します。<br/>            読み取り/書き込み **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/table/shape_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/table/is_grouped/) | シェイプがグループ化されているかどうかを決定します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/table/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/table/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/table/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/table/graphical_object_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`rows`](/slides/python-net/ja/aspose.slides/table/rows/) | 行のコレクションを返します。<br/>            読み取り専用 [`IRowCollection`](/slides/python-net/ja/aspose.slides/irowcollection)。 |
| [`columns`](/slides/python-net/ja/aspose.slides/table/columns/) | 列のコレクションを返します。<br/>            読み取り専用 [`IColumnCollection`](/slides/python-net/ja/aspose.slides/icolumncollection)。 |
| [`table_format`](/slides/python-net/ja/aspose.slides/table/table_format/) | このテーブルの書式設定プロパティを含む TableFormat オブジェクトを返します。<br/>            読み取り専用 [`ITableFormat`](/slides/python-net/ja/aspose.slides/itableformat)。 |
| [`style_preset`](/slides/python-net/ja/aspose.slides/table/style_preset/) | 組み込みテーブルスタイルを取得または設定します。<br/>            読み取り/書き込み [`TableStylePreset`](/slides/python-net/ja/aspose.slides/tablestylepreset)。 |
| [`right_to_left`](/slides/python-net/ja/aspose.slides/table/right_to_left/) | テーブルが右から左への読み順かどうかを決定します。<br/>            読み書き **bool**。 |
| [`first_row`](/slides/python-net/ja/aspose.slides/table/first_row/) | テーブルの最初の行が特別な書式で描画されるかどうかを決定します。<br/>            読み取り/書き込み **bool**。 |
| [`first_col`](/slides/python-net/ja/aspose.slides/table/first_col/) | テーブルの最初の列が特別な書式で描画されるかどうかを決定します。<br/>            読み取り/書き込み **bool**。 |
| [`last_row`](/slides/python-net/ja/aspose.slides/table/last_row/) | テーブルの最後の行が特別な書式で描画されるかどうかを決定します。<br/>            読み取り/書き込み **bool**。 |
| [`last_col`](/slides/python-net/ja/aspose.slides/table/last_col/) | テーブルの最後の列が特別な書式で描画されるかどうかを決定します。<br/>            読み取り/書き込み **bool**。 |
| [`horizontal_banding`](/slides/python-net/ja/aspose.slides/table/horizontal_banding/) | 偶数行が異なる書式で描画されるかどうかを決定します。<br/>            読み取り/書き込み **bool**。 |
| [`vertical_banding`](/slides/python-net/ja/aspose.slides/table/vertical_banding/) | 偶数列が異なる書式で描画されるかどうかを決定します。<br/>            読み取り/書き込み **bool**。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/table/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/table/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`set_text_format(self, source)`](/slides/python-net/ja/aspose.slides/table/set_text_format/#iportionformat) | 定義された部分書式プロパティをすべてのテーブルセルの部分に設定します。 |
| [`set_text_format(self, source)`](/slides/python-net/ja/aspose.slides/table/set_text_format/#iparagraphformat) | 定義された段落書式プロパティをすべてのテーブルセルの段落に設定します。 |
| [`set_text_format(self, source)`](/slides/python-net/ja/aspose.slides/table/set_text_format/#itextframeformat) | 定義されたテキストフレーム書式プロパティをすべてのテーブルセルのテキストフレームに設定します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/table/remove_placeholder/#) | このシェイプがプレースホルダーでないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/table/add_placeholder/#iplaceholder) | プレースホルダーがない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/table/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトやマスタースライドからのシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/table/get_visual_bounds/#) | シェイプの描画内容から計算された視覚的境界を取得します。 |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/ja/aspose.slides/table/merge_cells/#icell-icell-bool) | 隣接するセルを結合します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`Table`](/slides/python-net/ja/aspose.slides/table)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)