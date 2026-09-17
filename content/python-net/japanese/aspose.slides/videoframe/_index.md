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

The VideoFrame type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/videoframe/is_text_holder/) | 形状が TextHolder_PPT かどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides/videoframe/placeholder/) | 形状のプレースホルダーを返します。形状にプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/videoframe/custom_data/) | 形状のカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/videoframe/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides/videoframe/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides/videoframe/line_format/) | 形状の線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定の形状タイプでは None を返す場合があります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/videoframe/three_d_format/) | 形状の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定の形状タイプでは None を返す場合があります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/videoframe/effect_format/) | 形状に適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定の形状タイプでは None を返す場合があります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/videoframe/fill_format/) | 形状の塗り書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りプロパティを持たない特定の形状タイプでは None を返す場合があります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/videoframe/hyperlink_click/) | マウスクリック時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/videoframe/hyperlink_mouse_over/) | マウスオーバー時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/videoframe/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides/videoframe/hidden/) | 形状が非表示かどうかを決定します。<br/>            読み書き **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/videoframe/z_order_position/) | z 順序における形状の位置を返します。<br/>            Shapes[0] は z 順序の最背面にある形状を返し、<br/>            Shapes[Shapes.Count - 1] は最前面にある形状を返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/videoframe/connection_site_count/) | 形状上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides/videoframe/rotation/) | 指定された形状が z 軸周りで回転している角度（度）を取得または設定します。<br/>            正の値は時計回り、負の値は反時計回りを示します。<br/>            読み書き **float**. |
| [`x`](/slides/python-net/ja/aspose.slides/videoframe/x/) | 形状左上隅の x 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/videoframe/y/) | 形状左上隅の y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/videoframe/width/) | 形状の幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/videoframe/height/) | 形状の高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/videoframe/black_white_mode/) | 形状が白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides/videoframe/unique_id/) | アドインやその他のコードで使用することを目的とした、プレゼンテーションスコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムから再割り当て可能であるため、永続的なユニークキーとして扱ってはなりません。<br/>            読み取り専用 **int**。. <br/>            なお、[`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id) も参照してください。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/videoframe/office_interop_shape_id/) | 形状の存続期間中一定であるスライドスコープのユニーク識別子を返し、<br/>            PowerPoint またはインターロップコードが文書内の任意の場所から形状を確実に参照できるようにします。<br/>            読み取り専用 **int**。. <br/>            なお、[`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id) も参照してください。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/videoframe/alternative_text/) | 形状に関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/videoframe/alternative_text_title/) | 形状に関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`name`](/slides/python-net/ja/aspose.slides/videoframe/name/) | 形状の名前を取得または設定します。<br/>            None であってはならず、必要に応じて空文字列を使用してください。<br/>            読み書き **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/videoframe/is_decorative/) | 装飾としてマークするオプションを取得または設定します。<br/>            読み書き **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/videoframe/shape_lock/) | 形状のロック情報を返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/videoframe/is_grouped/) | 形状がグループ化されているかどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides/videoframe/parent_group/) | 形状がグループ化されている場合は親 GroupShape オブジェクトを返し、そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides/videoframe/slide/) | 形状の親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides/videoframe/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ja/aspose.slides/videoframe/shape_style/) | 形状のスタイルオブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ja/aspose.slides/videoframe/shape_type/) | PictureFrame の AutoShape タイプを取得または設定します。<br/>            設定可能な項目は集合 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) のすべてですが、以下の各種線は除外されます：<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            読み書き [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ja/aspose.slides/videoframe/adjustments/) | 形状の調整値のコレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/ja/aspose.slides/videoframe/picture_frame_lock/) | 形状のロック情報を返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/ja/aspose.slides/videoframe/picture_format/) | 画像フレームの PictureFillFormat オブジェクトを返します。<br/>            読み取り専用 [`IPictureFillFormat`](/slides/python-net/ja/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/ja/aspose.slides/videoframe/relative_scale_height/) | 画像フレームの高さのスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。<br/>            読み書き **float**. |
| [`relative_scale_width`](/slides/python-net/ja/aspose.slides/videoframe/relative_scale_width/) | 画像フレームの幅のスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。<br/>            読み書き **float**. |
| [`is_cameo`](/slides/python-net/ja/aspose.slides/videoframe/is_cameo/) | PictureFrame が Cameo オブジェクトかどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`rewind_video`](/slides/python-net/ja/aspose.slides/videoframe/rewind_video/) | 動画が再生終了後に自動的に開始位置へ巻き戻されるかどうかを決定します。<br/>            読み書き **bool**. |
| [`play_loop_mode`](/slides/python-net/ja/aspose.slides/videoframe/play_loop_mode/) | 動画がループ再生されるかどうかを決定します。<br/>            読み書き **bool**. |
| [`hide_at_showing`](/slides/python-net/ja/aspose.slides/videoframe/hide_at_showing/) | VideoFrame が非表示かどうかを決定します。<br/>            読み書き **bool**. |
| [`volume`](/slides/python-net/ja/aspose.slides/videoframe/volume/) | 音声ボリュームを取得または設定します。<br/>            読み書き [`AudioVolumeMode`](/slides/python-net/ja/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/ja/aspose.slides/videoframe/play_mode/) | 動画の再生モードを取得または設定します。<br/>            読み書き [`VideoPlayModePreset`](/slides/python-net/ja/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/ja/aspose.slides/videoframe/full_screen_mode/) | 動画が全画面モードで表示されるかどうかを決定します。<br/>            読み書き **bool**. |
| [`link_path_long`](/slides/python-net/ja/aspose.slides/videoframe/link_path_long/) | VideoFrame にリンクされた動画ファイルの名前を取得または設定します。<br/>            読み書き **str**. |
| [`embedded_video`](/slides/python-net/ja/aspose.slides/videoframe/embedded_video/) | 埋め込み動画オブジェクトを取得または設定します。<br/>            読み書き [`IVideo`](/slides/python-net/ja/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/ja/aspose.slides/videoframe/trim_from_start/) | トリム開始 [ms] |
| [`trim_from_end`](/slides/python-net/ja/aspose.slides/videoframe/trim_from_end/) | トリム終了 [ms] |
| [`caption_tracks`](/slides/python-net/ja/aspose.slides/videoframe/caption_tracks/) | 動画フレームに関連付けられたクローズドキャプションのコレクションを取得します。<br/>             このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](/slides/python-net/ja/aspose.slides/icaptionscollection) を返します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_image/#) | 形状のサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape の形状サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | 形状のサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/videoframe/write_as_svg/#iorawiobase) | 形状の内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 形状の内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/videoframe/remove_placeholder/#) | この形状がプレースホルダーでないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/videoframe/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_base_placeholder/#) | 基本的なプレースホルダー形状（現在の形状が継承しているレイアウトまたはマスタースライド上の形状）を返します。<br/>            現在の形状が継承されていない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_visual_bounds/#) | レンダリングされたコンテンツから計算された形状の視覚的境界を取得します。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/videoframe/get_geometry_paths/#) | ジオメトリ形状のパスのコピーを返します。座標は形状の左上隅を基準としています。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトから形状のジオメトリを更新します。座標は形状の左上隅を基準とする必要があります。<br/>             形状のタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列から形状のジオメトリを更新します。座標は形状の左上隅を基準とする必要があります。<br/>             形状のタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/videoframe/create_shape_elements/#) | 形状の要素の配列を作成して返します。 |

### 参照
* クラス [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape)
* クラス [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`VideoFrame`](/slides/python-net/ja/aspose.slides/videoframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)