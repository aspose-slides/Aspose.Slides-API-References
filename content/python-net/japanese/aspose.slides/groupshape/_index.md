---
title: GroupShape class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/groupshape/
---
## GroupShape クラス

スライド上のシェイプのグループを表します。

**継承:**[`GroupShape`](/slides/python-net/ja/aspose.slides/groupshape) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

GroupShape 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/groupshape/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/groupshape/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/groupshape/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/groupshape/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/groupshape/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/groupshape/line_format/) | シェイプのライン書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: GroupShape オブジェクトはラインプロパティを持たないため、None を返します。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/groupshape/three_d_format/) | シェイプの 3D エフェクトプロパティを持つ ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/groupshape/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/groupshape/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/groupshape/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/groupshape/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/groupshape/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/groupshape/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/groupshape/z_order_position/) | z オーダーにおけるシェイプの位置を返します。<br/>            Shapes[0] は z オーダーの最背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は z オーダーの最前面にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/groupshape/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/groupshape/rotation/) | 指定されたシェイプが z 軸周りに回転している度数を取得または設定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。<br/>            読み書き可能 **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/groupshape/x/) | シェイプの左上隅の x 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/groupshape/y/) | シェイプの左上隅の y 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/groupshape/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/groupshape/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/groupshape/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/groupshape/unique_id/) | アドインや他のコードが使用することを想定した、プレゼンテーションスコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的なユニークキーとして扱うべきではありません。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/groupshape/office_interop_shape_id/) | シェイプの存続期間中一定で、ドキュメント内の任意の場所から PowerPoint やインタープコードがシェイプを確実に参照できるようにする、スライドスコープのユニーク識別子を返します。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/groupshape/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/groupshape/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/groupshape/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/groupshape/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します<br/>            読み書き可能 **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/groupshape/shape_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGroupShapeLock`](/slides/python-net/ja/aspose.slides/igroupshapelock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/groupshape/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/groupshape/parent_group/) | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/groupshape/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/groupshape/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`group_shape_lock`](/slides/python-net/ja/aspose.slides/groupshape/group_shape_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGroupShapeLock`](/slides/python-net/ja/aspose.slides/igroupshapelock)。 |
| [`shapes`](/slides/python-net/ja/aspose.slides/groupshape/shapes/) | グループ内のシェイプコレクションを返します。<br/>            読み取り専用 [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/groupshape/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/groupshape/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/groupshape/remove_placeholder/#) | このシェイプがプレースホルダーでないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/groupshape/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/groupshape/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（現在のシェイプが継承元となるレイアウトまたはマスタースライドからのシェイプ）を返します。<br/>            現在のシェイプが継承していない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/groupshape/get_visual_bounds/#) | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |

### 参照
* クラス [`GroupShape`](/slides/python-net/ja/aspose.slides/groupshape)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)