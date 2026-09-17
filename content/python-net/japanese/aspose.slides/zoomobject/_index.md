---
title: ZoomObject class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/zoomobject/
---
## ZoomObject クラス

スライド内の Zoom オブジェクトを表します。

**継承:**[`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

ZoomObject 型は次のメンバーを公開しています。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/zoomobject/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/zoomobject/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/zoomobject/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/zoomobject/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/zoomobject/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/zoomobject/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のタイプのシェイプでは None を返す可能性があります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/zoomobject/three_d_format/) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のタイプのシェイプでは None を返す可能性があります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/zoomobject/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のタイプのシェイプでは None を返す可能性があります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/zoomobject/fill_format/) | シェイプの塗り書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りプロパティを持たない特定のタイプのシェイプでは None を返す可能性があります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/zoomobject/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/zoomobject/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/zoomobject/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/zoomobject/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/zoomobject/z_order_position/) | シェイプの Z 順序における位置を返します。<br/>            Shapes[0] は Z 順序の背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は Z 順序の前面にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/zoomobject/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/zoomobject/rotation/) | 指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。<br/>            正の値は時計回り回転を示し、負の値は反時計回り回転を示します。<br/>            読み書き **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/zoomobject/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/zoomobject/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/zoomobject/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/zoomobject/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/zoomobject/black_white_mode/) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/zoomobject/unique_id/) | アドインや他のコードで使用することを想定した、プレゼンテーション内でスコープされた内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/zoomobject/office_interop_shape_id/) | スライドスコープの一意識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint またはインターロップコードがドキュメント内の任意の位置からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/zoomobject/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/zoomobject/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/zoomobject/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/zoomobject/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            Reed/write **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/zoomobject/shape_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/zoomobject/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/zoomobject/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。それ以外の場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/zoomobject/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/zoomobject/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/zoomobject/graphical_object_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`image_type`](/slides/python-net/ja/aspose.slides/zoomobject/image_type/) | ズームオブジェクトの画像タイプを取得または設定します。<br/>            読み書き [`ZoomImageType`](/slides/python-net/ja/aspose.slides/zoomimagetype)。<br/>            デフォルト値: Preview |
| [`return_to_parent`](/slides/python-net/ja/aspose.slides/zoomobject/return_to_parent/) | スライドショー中のナビゲーション動作を取得または設定します。<br/>            読み書き **bool**。<br/>            デフォルト値: false |
| [`show_background`](/slides/python-net/ja/aspose.slides/zoomobject/show_background/) | ズームが宛先スライドの背景を使用するかどうかを指定する値を取得または設定します。<br/>            読み書き **bool**。<br/>            デフォルト値: true |
| [`zoom_image`](/slides/python-net/ja/aspose.slides/zoomobject/zoom_image/) | ズームオブジェクトの画像を取得または設定します。<br/>            読み書き [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)。 |
| [`transition_duration`](/slides/python-net/ja/aspose.slides/zoomobject/transition_duration/) | ズームとスライド間の遷移時間を取得または設定します。<br/>            読み書き **float**。<br/>            デフォルト値: 1.0f |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/zoomobject/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/zoomobject/remove_placeholder/#) | このシェイプがプレースホルダーでないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/zoomobject/get_base_placeholder/#) | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承されているレイアウトやマスタースライドからのシェイプ）。<br/>            継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/zoomobject/get_visual_bounds/#) | シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)