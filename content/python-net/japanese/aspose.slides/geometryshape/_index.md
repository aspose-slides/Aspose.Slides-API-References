---
title: GeometryShape class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/geometryshape/
---
## GeometryShape クラス

すべての幾何学的シェイプの親クラスを表します。

**継承:**[`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

GeometryShape 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/geometryshape/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides/geometryshape/placeholder/) | シェイプのプレースホルダーを返します。プレースホルダーが無い場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/geometryshape/custom_data/) | シェイプのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/geometryshape/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides/geometryshape/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides/geometryshape/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のシェイプでは None が返されることがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/geometryshape/three_d_format/) | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプでは None が返されることがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/geometryshape/effect_format/) | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/>            注: 効果プロパティを持たない特定のシェイプでは None が返されることがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/geometryshape/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のシェイプでは None が返されることがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/geometryshape/hyperlink_click/) | クリック時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/geometryshape/hyperlink_mouse_over/) | マウスオーバー時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/geometryshape/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides/geometryshape/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き可能 **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/geometryshape/z_order_position/) | シェイプの Z 順序における位置を返します。<br/>            Shapes[0] は Z 順序の最背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面にあるシェイプを返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/geometryshape/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides/geometryshape/rotation/) | 指定されたシェイプが Z 軸を中心に回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。<br/>            読み書き可能 **float**. |
| [`x`](/slides/python-net/ja/aspose.slides/geometryshape/x/) | シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/geometryshape/y/) | シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/geometryshape/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/geometryshape/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/geometryshape/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides/geometryshape/unique_id/) | アドインや他のコードが使用することを想定した、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能であるため、永続的な一意キーとして扱ってはなりません。<br/>            読み取り専用 **int**.<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/geometryshape/office_interop_shape_id/) | スライド スコープの一意識別子を返します。この識別子はシェイプの存続期間中は変わらず、PowerPoint や interop コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**.<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/geometryshape/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/geometryshape/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**. |
| [`name`](/slides/python-net/ja/aspose.slides/geometryshape/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/geometryshape/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き可能 **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/geometryshape/shape_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IBaseShapeLock`](/slides/python-net/ja/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/geometryshape/is_grouped/) | シェイプがグループ化されているかどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides/geometryshape/parent_group/) | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides/geometryshape/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides/geometryshape/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ja/aspose.slides/geometryshape/shape_style/) | シェイプのスタイル オブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type/) | ジオメトリ プリセット タイプを取得または設定します。<br/>            注: 値が変更されると、すべての調整値がデフォルトにリセットされます。<br/>            読み書き可能 [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ja/aspose.slides/geometryshape/adjustments/) | シェイプの調整値コレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/geometryshape/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape シェイプ サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/geometryshape/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダー プロパティを指定されたものに設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/geometryshape/get_base_placeholder/#) | 基本的なプレースホルダー シェイプ（レイアウトまたはマスタースライドから継承されたシェイプ）を返します。<br/>            継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/geometryshape/get_visual_bounds/#) | シェイプの描画内容から計算された視覚的境界を取得します。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/geometryshape/get_geometry_paths/#) | ジオメトリ シェイプのパスのコピーを返します。座標はシェイプ左上隅を基準とします。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプ左上隅を基準とする必要があります。<br/>            シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) 配列からシェイプのジオメトリを更新します。座標はシェイプ左上隅を基準とする必要があります。<br/>            シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/geometryshape/create_shape_elements/#) | シェイプ要素の配列を作成して返します。 |

### 参照
* クラス [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)