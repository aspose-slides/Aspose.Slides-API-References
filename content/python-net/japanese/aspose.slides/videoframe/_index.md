---
title: VideoFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/videoframe/
---
## VideoFrame クラス

スライド上のビデオクリップを表します。

**継承:**[`VideoFrame`](/slides/python-net/ja/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

VideoFrame 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/videoframe/is_text_holder/) | 形状が TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/videoframe/placeholder/) | 形状のプレースホルダーを返します。形状にプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/videoframe/custom_data/) | 形状のカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/videoframe/raw_frame/) | 生の形状フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/videoframe/frame/) | 形状フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/videoframe/line_format/) | 形状の線の書式設定プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定の形状タイプの場合、None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/videoframe/three_d_format/) | 形状の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定の形状タイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/videoframe/effect_format/) | 形状に適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定の形状タイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/videoframe/fill_format/) | 形状の塗りつぶし書式設定プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定の形状タイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/videoframe/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/videoframe/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/videoframe/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/videoframe/hidden/) | 形状が非表示かどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/videoframe/z_order_position/) | 形状の Z 順序における位置を返します。<br/>            Shapes[0] は Z 順序の背面にある形状を返し、<br/>            Shapes[Shapes.Count - 1] は前面にある形状を返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/videoframe/connection_site_count/) | 形状上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/videoframe/rotation/) | 指定された形状が Z 軸周りに回転した角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを表します。<br/>            読み書き可能 **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/videoframe/x/) | 形状の左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/videoframe/y/) | 形状の左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/videoframe/width/) | 形状の幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/videoframe/height/) | 形状の高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/videoframe/black_white_mode/) | プロパティは、形状が白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/videoframe/unique_id/) | アドインや他のコードで使用することを意図した、内部のプレゼンテーションスコープの識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/videoframe/office_interop_shape_id/) | スライドスコープの一意識別子を返します。この識別子は形状の存続期間中は変更されず、PowerPoint や Interop コードが文書内の任意の場所から形状を確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/videoframe/alternative_text/) | 形状に関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/videoframe/alternative_text_title/) | 形状に関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/videoframe/name/) | 形状の名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/videoframe/is_decorative/) | ‘Mark as decorative’ オプションを取得または設定します。<br/>            読み書き可能 **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/videoframe/shape_lock/) | 形状のロック情報を返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/videoframe/is_grouped/) | 形状がグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/videoframe/parent_group/) | 形状がグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/videoframe/slide/) | 形状の親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/videoframe/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`shape_style`](/slides/python-net/ja/aspose.slides/videoframe/shape_style/) | 形状のスタイルオブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/ja/aspose.slides/videoframe/shape_type/) | PictureFrame の AutoShape タイプを取得または設定します。<br/>            許容される項目は集合 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) のすべてです。ただし、以下のすべての線種は除外されます：<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            読み書き可能 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/ja/aspose.slides/videoframe/adjustments/) | 形状の調整値コレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection)。 |
| [`picture_frame_lock`](/slides/python-net/ja/aspose.slides/videoframe/picture_frame_lock/) | 形状のロック情報を返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock)。 |
| [`picture_format`](/slides/python-net/ja/aspose.slides/videoframe/picture_format/) | ピクチャーフレームの PictureFillFormat オブジェクトを返します。<br/>            読み取り専用 [`IPictureFillFormat`](/slides/python-net/ja/aspose.slides/ipicturefillformat)。 |
| [`relative_scale_height`](/slides/python-net/ja/aspose.slides/videoframe/relative_scale_height/) | ピクチャーフレームの高さのスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。<br/>            読み書き可能 **float**。 |
| [`relative_scale_width`](/slides/python-net/ja/aspose.slides/videoframe/relative_scale_width/) | ピクチャーフレームの幅のスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。<br/>            読み書き可能 **float**。 |
| [`is_cameo`](/slides/python-net/ja/aspose.slides/videoframe/is_cameo/) | PictureFrame が Cameo オブジェクトかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`rewind_video`](/slides/python-net/ja/aspose.slides/videoframe/rewind_video/) | ビデオが再生完了後に自動的に先頭へ巻き戻されるかどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`play_loop_mode`](/slides/python-net/ja/aspose.slides/videoframe/play_loop_mode/) | ビデオがループ再生されるかどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`hide_at_showing`](/slides/python-net/ja/aspose.slides/videoframe/hide_at_showing/) | VideoFrame が非表示かどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`volume`](/slides/python-net/ja/aspose.slides/videoframe/volume/) | オーディオボリュームを取得または設定します。<br/>            読み書き可能 [`AudioVolumeMode`](/slides/python-net/ja/aspose.slides/audiovolumemode)。 |
| [`volume_value`](/slides/python-net/ja/aspose.slides/videoframe/volume_value/) | ビデオボリュームをパーセンテージで正確に取得または設定します。<br/>            値は 0 から 100 のパーセンテージで表されます。このプロパティを使用して、[`VideoFrame.volume`](/slides/python-net/ja/aspose.slides/videoframe/volume) プロパティで利用できる事前定義レベルよりも細かいボリューム値を読み書きできます。<br/>            読み書き可能 **float**。 |
| [`play_mode`](/slides/python-net/ja/aspose.slides/videoframe/play_mode/) | ビデオの再生モードを取得または設定します。<br/>            読み書き可能 [`VideoPlayModePreset`](/slides/python-net/ja/aspose.slides/videoplaymodepreset)。 |
| [`full_screen_mode`](/slides/python-net/ja/aspose.slides/videoframe/full_screen_mode/) | ビデオが全画面モードで表示されるかどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`link_path_long`](/slides/python-net/ja/aspose.slides/videoframe/link_path_long/) | VideoFrame にリンクされたビデオファイルの名前を取得または設定します。<br/>            読み書き可能 **str**。 |
| [`embedded_video`](/slides/python-net/ja/aspose.slides/videoframe/embedded_video/) | 埋め込みビデオオブジェクトを取得または設定します。<br/>            読み書き可能 [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo)。 |
| [`trim_from_start`](/slides/python-net/ja/aspose.slides/videoframe/trim_from_start/) | トリム開始 [ms] |
| [`trim_from_end`](/slides/python-net/ja/aspose.slides/videoframe/trim_from_end/) | トリム終了 [ms] |
| [`caption_tracks`](/slides/python-net/ja/aspose.slides/videoframe/caption_tracks/) | ビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。<br/>            このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](/slides/python-net/ja/aspose.slides/icaptionscollection) を返します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_image/#) | 形状のサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape の形状サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | 形状のサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Shape の内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape の内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/videoframe/remove_placeholder/#) | この形状がプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/videoframe/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_base_placeholder/#) | 基本的なプレースホルダー形状（レイアウトまたはマスタースライドから継承された形状）を返します。<br/>            現在の形状が継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_visual_bounds/#) | レンダリングされたコンテンツから計算された形状の視覚的境界を取得します。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_geometry_paths/#) | ジオメトリ形状のパスのコピーを返します。座標は形状の左上隅を基準とした相対座標です。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトから形状ジオメトリを更新します。座標は形状の左上隅を基準とした相対座標である必要があります。<br/>            形状のタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) 配列から形状ジオメトリを更新します。座標は形状の左上隅を基準とした相対座標である必要があります。<br/>            形状のタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/videoframe/create_shape_elements/#) | 形状の要素配列を作成して返します。 |

### 参照
* クラス [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape)
* クラス [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`VideoFrame`](/slides/python-net/ja/aspose.slides/videoframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)