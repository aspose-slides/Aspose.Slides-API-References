---
title: SmartArt class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartart/
---
## SmartArt クラス

SmartArt ダイアグラムを表します

**継承:**[`SmartArt`](/slides/python-net/ja/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

SmartArt 型は次のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides.smartart/smartart/is_text_holder/) | シェイプが TextHolder_PPT かどうかを決定します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides.smartart/smartart/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides.smartart/smartart/custom_data/) | シェイプのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides.smartart/smartart/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides.smartart/smartart/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides.smartart/smartart/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides.smartart/smartart/three_d_format/) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides.smartart/smartart/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides.smartart/smartart/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides.smartart/smartart/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides.smartart/smartart/hyperlink_manager/) | ハイパーリンク マネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides.smartart/smartart/hidden/) | シェイプが非表示かどうかを決定します。<br/>            読み書き **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides.smartart/smartart/z_order_position/) | シェイプの Z 順序内での位置を返します。<br/>            Shapes[0] は Z 順序の背面のシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面のシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides.smartart/smartart/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides.smartart/smartart/rotation/) | 指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。<br/>            正の値は時計回り、負の値は反時計回りを示します。<br/>            読み書き **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides.smartart/smartart/x/) | シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides.smartart/smartart/y/) | シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides.smartart/smartart/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides.smartart/smartart/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides.smartart/smartart/black_white_mode/) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides.smartart/smartart/unique_id/) | アドインやその他のコードで使用することを意図した、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的なユニークキーとして扱うべきではありません。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides.smartart/smartart/office_interop_shape_id/) | スライド スコープのユニーク識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint やインターオプコードが文書内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides.smartart/smartart/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides.smartart/smartart/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides.smartart/smartart/name/) | シェイプの名前を取得または設定します。<br/>            None ではいけません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides.smartart/smartart/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides.smartart/smartart/shape_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides.smartart/smartart/is_grouped/) | シェイプがグループ化されているかどうかを決定します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides.smartart/smartart/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides.smartart/smartart/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides.smartart/smartart/presentation/) | スライドの父プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides.smartart/smartart/graphical_object_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`all_nodes`](/slides/python-net/ja/aspose.slides.smartart/smartart/all_nodes/) | SmartArt オブジェクト内のすべてのノードのコレクションを返します。<br/>            読み取り専用 [`ISmartArtNodeCollection`](/slides/python-net/ja/aspose.slides.smartart/ismartartnodecollection)。 |
| [`nodes`](/slides/python-net/ja/aspose.slides.smartart/smartart/nodes/) | SmartArt オブジェクトのルート ノードのコレクションを返します。<br/>            読み取り専用 [`ISmartArtNodeCollection`](/slides/python-net/ja/aspose.slides.smartart/ismartartnodecollection)。 |
| [`layout`](/slides/python-net/ja/aspose.slides.smartart/smartart/layout/) | SmartArt オブジェクトのレイアウトを取得または設定します。<br/>            読み書き [`SmartArtLayoutType`](/slides/python-net/ja/aspose.slides.smartart/smartartlayouttype)。 |
| [`quick_style`](/slides/python-net/ja/aspose.slides.smartart/smartart/quick_style/) | SmartArt オブジェクトのクイック スタイルを取得または設定します。<br/>            読み書き [`SmartArtQuickStyleType`](/slides/python-net/ja/aspose.slides.smartart/smartartquickstyletype)。 |
| [`color_style`](/slides/python-net/ja/aspose.slides.smartart/smartart/color_style/) | SmartArt オブジェクトのカラー スタイルを取得または設定します。<br/>            読み書き [`SmartArtColorType`](/slides/python-net/ja/aspose.slides.smartart/smartartcolortype)。 |
| [`is_reversed`](/slides/python-net/ja/aspose.slides.smartart/smartart/is_reversed/) | ダイアグラムが反転に対応している場合、SmartArt 図の左から右 (LTR) または右から左 (RTL) の状態を取得または設定します。<br/>            読み書き **bool**。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides.smartart/smartart/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプ サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides.smartart/smartart/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | プレースホルダーがない場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides.smartart/smartart/get_base_placeholder/#) | 基本的なプレースホルダー シェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドのシェイプ）を返します。<br/>            継承されていない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides.smartart/smartart/get_visual_bounds/#) | シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`SmartArt`](/slides/python-net/ja/aspose.slides.smartart/smartart)
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)