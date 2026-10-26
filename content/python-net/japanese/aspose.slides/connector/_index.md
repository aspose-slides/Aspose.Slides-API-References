---
title: Connector class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/connector/
---
## Connector クラス

コネクタを表します。

**継承:**[`Connector`](/slides/python-net/ja/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

Connector 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/connector/is_text_holder/) | シェイプが TextHolder_PPT であるかどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides/connector/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/connector/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/connector/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides/connector/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides/connector/line_format/) | シェイプの線フォーマットプロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のシェイプタイプの場合、None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/connector/three_d_format/) | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/connector/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のシェイプタイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/connector/fill_format/) | シェイプの塗りつぶしフォーマットプロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のシェイプタイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/connector/hyperlink_click/) | マウスクリック時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/connector/hyperlink_mouse_over/) | マウスオーバー時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/connector/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides/connector/hidden/) | シェイプが非表示かどうかを決定します。<br/>            読み書き **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/connector/z_order_position/) | シェイプの z 順序における位置を返します。<br/>            Shapes[0] は z 順序の最背面のシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面のシェイプを返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/connector/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides/connector/rotation/) | 指定されたシェイプが z 軸周りに回転する角度（度）を取得または設定します。<br/>            正の値は時計回り、負の値は反時計回りを示します。<br/>            読み書き **float**. |
| [`x`](/slides/python-net/ja/aspose.slides/connector/x/) | シェイプ左上隅の x 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/connector/y/) | シェイプ左上隅の y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/connector/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/connector/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/connector/black_white_mode/) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides/connector/unique_id/) | アドインや他のコードで使用することを想定した、プレゼンテーションスコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/connector/office_interop_shape_id/) | スライドスコープの一意識別子を返します。この識別子はシェイプのライフタイム中は一定で、PowerPoint またはインターロップコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/connector/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/connector/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`name`](/slides/python-net/ja/aspose.slides/connector/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/connector/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/connector/shape_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IConnectorLock`](/slides/python-net/ja/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/connector/is_grouped/) | シェイプがグループ化されているかどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides/connector/parent_group/) | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返し、そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides/connector/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides/connector/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ja/aspose.slides/connector/shape_style/) | シェイプのスタイルオブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ja/aspose.slides/connector/shape_type/) | AutoShape のタイプを取得または設定します。<br/>            読み書き [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ja/aspose.slides/connector/adjustments/) | シェイプの調整値のコレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/ja/aspose.slides/connector/connector_lock/) | コネクタのロック状態を返します。<br/>            読み取り専用 [`IConnectorLock`](/slides/python-net/ja/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/ja/aspose.slides/connector/start_shape_connected_to/) | コネクタの開始点を接続するシェイプを取得または設定します。<br/>            読み書き [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/ja/aspose.slides/connector/end_shape_connected_to/) | コネクタの終了点を接続するシェイプを取得または設定します。<br/>            読み書き [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/ja/aspose.slides/connector/start_shape_connection_site_index/) | 開始シェイプの接続ポイントのインデックスを取得または設定します。<br/>            読み書き **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/ja/aspose.slides/connector/end_shape_connection_site_index/) | 終了シェイプの接続ポイントのインデックスを取得または設定します。<br/>            読み書き **int**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/connector/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/connector/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/connector/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/connector/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/connector/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/connector/get_visual_bounds/#) | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/connector/get_geometry_paths/#) | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準としています。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/connector/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。<br/>             シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。<br/>             シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/connector/create_shape_elements/#) | シェイプの要素配列を作成して返します。 |
| [`reroute(self)`](/slides/python-net/ja/aspose.slides/connector/reroute/#) | コネクタの経路を再設定し、接続されるシェイプ間の可能な最短パスを取らせます。 |

### 参照
* クラス [`Connector`](/slides/python-net/ja/aspose.slides/connector)
* クラス [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)