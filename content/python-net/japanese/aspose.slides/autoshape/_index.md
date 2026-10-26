---
title: AutoShape class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/autoshape/
---
## AutoShape クラス

AutoShape を表します。

**継承:**[`AutoShape`](/slides/python-net/ja/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

AutoShape 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/autoshape/is_text_holder/) | シェイプが TextHolder_PPT かどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides/autoshape/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/autoshape/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/autoshape/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides/autoshape/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides/autoshape/line_format/) | シェイプの線フォーマットプロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/autoshape/three_d_format/) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/autoshape/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/autoshape/fill_format/) | シェイプの塗りつぶしフォーマットプロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/autoshape/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/autoshape/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/autoshape/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides/autoshape/hidden/) | シェイプが非表示かどうかを決定します。<br/>            読み書き **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/autoshape/z_order_position/) | シェイプの Z 順序内での位置を返します。<br/>            Shapes[0] は Z 順序の最背面のシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面のシェイプを返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/autoshape/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides/autoshape/rotation/) | 指定されたシェイプが Z 軸周りに回転する角度（度数）を取得または設定します。<br/>            正の値は時計回りの回転、負の値は反時計回りの回転を示します。<br/>            読み書き **float**. |
| [`x`](/slides/python-net/ja/aspose.slides/autoshape/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/autoshape/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/autoshape/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/autoshape/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/autoshape/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides/autoshape/unique_id/) | アドインやその他のコードで使用することを目的とした、プレゼンテーションスコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当てできるため、永続的な一意キーとして扱ってはなりません。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/autoshape/office_interop_shape_id/) | スライドスコープの一意識別子を返し、シェイプの寿命中は一定で、PowerPoint やインターオペコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/autoshape/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/autoshape/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`name`](/slides/python-net/ja/aspose.slides/autoshape/name/) | シェイプの名前を取得または設定します。<br/>            None であってはいけません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/autoshape/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/autoshape/shape_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IAutoShapeLock`](/slides/python-net/ja/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/autoshape/is_grouped/) | シェイプがグループ化されているかどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides/autoshape/parent_group/) | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返し、そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides/autoshape/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides/autoshape/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/ja/aspose.slides/autoshape/shape_style/) | シェイプのスタイルオブジェクトを返します。<br/>            読み取り専用 [`IShapeStyle`](/slides/python-net/ja/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/ja/aspose.slides/autoshape/shape_type/) | ジオメトリのプリセットタイプを取得または設定します。<br/>            注: 値を変更すると、すべての調整値はデフォルト値にリセットされます。<br/>            読み書き [`ShapeType`](/slides/python-net/ja/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/ja/aspose.slides/autoshape/adjustments/) | シェイプの調整値のコレクションを返します。<br/>            読み取り専用 [`IAdjustValueCollection`](/slides/python-net/ja/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/ja/aspose.slides/autoshape/auto_shape_lock/) | オートシェイプのロック情報を返します。<br/>            読み取り専用 [`IAutoShapeLock`](/slides/python-net/ja/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/ja/aspose.slides/autoshape/text_frame/) | AutoShape の TextFrame オブジェクトを返します。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/ja/aspose.slides/autoshape/use_background_fill/) | このオートシェイプがスタイルまたは塗りつぶしフォーマットで指定されたものではなく、スライドの背景塗りで塗りつぶすかどうかを決定します。<br/>            読み書き **bool**. |
| [`is_text_box`](/slides/python-net/ja/aspose.slides/autoshape/is_text_box/) | シェイプがテキストボックスかどうかを指定します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/autoshape/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/autoshape/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/autoshape/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/autoshape/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/autoshape/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトやマスタースライドからのシェイプ）を返します。<br/>            継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/autoshape/get_visual_bounds/#) | シェイプのレンダリングされたコンテンツから計算されたビジュアル境界を取得します。 |
| [`get_geometry_paths(self)`](/slides/python-net/ja/aspose.slides/autoshape/get_geometry_paths/#) | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準としています。 |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/ja/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。<br/>             シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/ja/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | [`IGeometryPath`](/slides/python-net/ja/aspose.slides/igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。<br/>             シェイプのタイプ ([`GeometryShape.shape_type`](/slides/python-net/ja/aspose.slides/geometryshape/shape_type)) を [`ShapeType.CUSTOM`](/slides/python-net/ja/aspose.slides/shapetype/CUSTOM) に変更します。 |
| [`create_shape_elements(self)`](/slides/python-net/ja/aspose.slides/autoshape/create_shape_elements/#) | シェイプの要素の配列を作成し、返します。 |
| [`add_text_frame(self, text)`](/slides/python-net/ja/aspose.slides/autoshape/add_text_frame/#str) | シェイプに新しい TextFrame を追加します。<br/>            すでに TextFrame が存在する場合は、テキストを単に変更します。 |

### 参照
* クラス [`AutoShape`](/slides/python-net/ja/aspose.slides/autoshape)
* クラス [`GeometryShape`](/slides/python-net/ja/aspose.slides/geometryshape)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)