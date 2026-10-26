---
title: PictureFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/pictureframe/
---
## PictureFrame クラス

画像を内部に持つフレームを表します。

**継承:**[`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

PictureFrame 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/pictureframe/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/pictureframe/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/pictureframe/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/pictureframe/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/pictureframe/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/pictureframe/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のシェイプタイプでは None を返す場合があります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/pictureframe/three_d_format/) | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプでは None を返す場合があります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/pictureframe/effect_format/) | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/>            注: 効果プロパティを持たない特定のシェイプタイプでは None を返す場合があります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/pictureframe/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは None を返す場合があります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/pictureframe/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/pictureframe/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/pictureframe/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/pictureframe/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/pictureframe/z_order_position/) | シェイプの Z 注文内の位置を返します。Shapes[0] は Z 注文の背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/pictureframe/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/pictureframe/rotation/) | 指定されたシェイプが Z 軸周りに回転した角度（度）を取得または設定します。正の値は時計回りの回転を、負の値は反時計回りの回転を示します。<br/>            読み書き可能 **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/pictureframe/x/) | シェイプの左上隅の x 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/pictureframe/y/) | シェイプの左上隅の y 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/pictureframe/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/pictureframe/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/pictureframe/black_white_mode/) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/pictureframe/unique_id/) | アドインやその他のコードで使用することを意図した、プレゼンテーションスコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/pictureframe/office_interop_shape_id/) | シェイプの存続期間中一定で、PowerPoint や interop コードがドキュメント内の任意の場所から確実にシェイプを参照できる、スライドスコープの一意識別子を返します。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/pictureframe/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/pictureframe/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/pictureframe/name/) | シェイプの名前を取得または設定します。None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/pictureframe/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き可能 **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/pictureframe/shape_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/pictureframe/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/pictureframe/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返し、そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/pictureframe/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/pictureframe/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`shape_style`](/slides/python-net/ja/aspose.slides/pictureframe/shape_style/) | シェイプのスタイルオブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle)。 |
| [`shape_type`](/slides/python-net/ja/aspose.slides/pictureframe/shape_type/) | PictureFrame の AutoShape タイプを取得または設定します。セット [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype) のすべての項目が許容されますが、以下のすべてのラインタイプは除外されます：<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            読み書き可能 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype)。 |
| [`adjustments`](/slides/python-net/ja/aspose.slides/pictureframe/adjustments/) | シェイプの調整値のコレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection)。 |
| [`picture_frame_lock`](/slides/python-net/ja/aspose.slides/pictureframe/picture_frame_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IPictureFrameLock`](/slides/python-net/ja/aspose.slides/ipictureframelock)。 |
| [`picture_format`](/slides/python-net/ja/aspose.slides/pictureframe/picture_format/) | ピクチャーフレームの PictureFillFormat オブジェクトを返します。<br/>            読み取り専用 [`IPictureFillFormat`](/slides/python-net/ja/aspose.slides/ipicturefillformat)。 |
| [`relative_scale_height`](/slides/python-net/ja/aspose.slides/pictureframe/relative_scale_height/) | ピクチャーフレームの高さ（元の画像サイズに対する相対スケール）を取得または設定します。値 1.0 は 100% に相当します。<br/>            読み書き可能 **float**。 |
| [`relative_scale_width`](/slides/python-net/ja/aspose.slides/pictureframe/relative_scale_width/) | ピクチャーフレームの幅（元の画像サイズに対する相対スケール）を取得または設定します。値 1.0 は 100% に相当します。<br/>            読み書き可能 **float**。 |
| [`is_cameo`](/slides/python-net/ja/aspose.slides/pictureframe/is_cameo/) | PictureFrame が Cameo オブジェクトかどうかを判断します。<br/>            読み取り専用 **bool**。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/pictureframe/get_image/#) | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/pictureframe/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/pictureframe/get_base_placeholder/#) | 現在のシェイプが継承されているレイアウトまたはマスタースライドからの基本プレースホルダーシェイプを返します。継承されていない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/pictureframe/get_visual_bounds/#) | シェイプのレンダリングされた内容から計算された視覚的境界を取得します。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/pictureframe/get_geometry_paths/#) | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準としています。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ（[`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)）を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ（[`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)）を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/pictureframe/create_shape_elements/#) | シェイプの要素の配列を作成して返します。 |

### 参照
* クラス [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape)
* クラス [`PictureFrame`](/slides/python-net/ja/aspose.slides/pictureframe)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)