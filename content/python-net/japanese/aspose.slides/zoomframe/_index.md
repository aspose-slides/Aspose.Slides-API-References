---
title: ZoomFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/zoomframe/
---
## ZoomFrame クラス

Represents a Slide Zoom object in a slide.

**Inheritance:**[`ZoomFrame`](/slides/python-net/ja/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

The ZoomFrame type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/zoomframe/is_text_holder/) | 形状が TextHolder_PPT かどうかを判定します。<br/> 読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/zoomframe/placeholder/) | 形状のプレースホルダーを返します。形状にプレースホルダーが無い場合は None を返します。<br/> 読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/zoomframe/custom_data/) | 形状のカスタム データを返します。<br/> 読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/zoomframe/raw_frame/) | 生の形状フレームのプロパティを取得または設定します。<br/> 読み取り/書き込み [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/zoomframe/frame/) | 形状フレームのプロパティを取得または設定します。<br/> 読み取り/書き込み [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/zoomframe/line_format/) | 形状の線書式プロパティを含む LineFormat オブジェクトを返します。<br/> 注: 線プロパティを持たない特定の形状タイプでは None を返すことがあります。<br/> 読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/zoomframe/three_d_format/) | 形状の 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/> 注: 3D プロパティを持たない特定の形状タイプでは None を返すことがあります。<br/> 読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/zoomframe/effect_format/) | 形状に適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/> 注: 効果プロパティを持たない特定の形状タイプでは None を返すことがあります。<br/> 読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/zoomframe/fill_format/) | 形状の塗り書式プロパティを含む FillFormat オブジェクトを返します。<br/> 注: 塗りプロパティを持たない特定の形状タイプでは None を返すことがあります。<br/> 読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/zoomframe/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/> 読み取り/書き込み [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/zoomframe/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/> 読み取り/書き込み [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/zoomframe/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/> 読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/zoomframe/hidden/) | 形状が非表示かどうかを判定します。<br/> 読み取り/書き込み **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/zoomframe/z_order_position/) | 形状の Z 順序における位置を返します。<br/> Shapes[0] は Z 順序の後方にある形状を返し、<br/> Shapes[Shapes.Count - 1] は前方にある形状を返します。<br/> 読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/zoomframe/connection_site_count/) | 形状上の接続ポイントの数を返します。<br/> 読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/zoomframe/rotation/) | 指定された形状が Z 軸を中心に回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。<br/> 読み取り/書き込み **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/zoomframe/x/) | 形状の左上隅の X 座標（ポイント単位）を取得または設定します。<br/> 読み取り/書き込み **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/zoomframe/y/) | 形状の左上隅の Y 座標（ポイント単位）を取得または設定します。<br/> 読み取り/書き込み **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/zoomframe/width/) | 形状の幅（ポイント単位）を取得または設定します。<br/> 読み取り/書き込み **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/zoomframe/height/) | 形状の高さ（ポイント単位）を取得または設定します。<br/> 読み取り/書き込み **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/zoomframe/black_white_mode/) | 形状が白黒表示モードでどのように描画されるかを指定するプロパティです。<br/> 読み取り/書き込み [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/zoomframe/unique_id/) | アドインや他のコードが使用することを想定した、プレゼンテーション スコープの内部識別子を返します。<br/> この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。<br/> 読み取り専用 **int**。<br/> 参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/zoomframe/office_interop_shape_id/) | 形状の存続期間中一定で、PowerPoint や Interop コードがドキュメント内の任意の場所から形状を確実に参照できるスライド スコープの一意識別子を返します。<br/> 読み取り専用 **int**。<br/> 参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/zoomframe/alternative_text/) | 形状に関連付けられた代替テキストを取得または設定します。<br/> 読み取り/書き込み **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/zoomframe/alternative_text_title/) | 形状に関連付けられた代替テキストのタイトルを取得または設定します。<br/> 読み取り/書き込み **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/zoomframe/name/) | 形状の名前を取得または設定します。<br/> None であってはなりません。必要に応じて空文字列を使用してください。<br/> 読み取り/書き込み **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/zoomframe/is_decorative/) | 装飾としてマークするオプションを取得または設定します。<br/> 読み取り/書き込み **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/zoomframe/shape_lock/) | 形状のロック状態を返します。<br/> 読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/zoomframe/is_grouped/) | 形状がグループ化されているかどうかを判定します。<br/> 読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/zoomframe/parent_group/) | 形状がグループ化されている場合は親 GroupShape オブジェクトを返し、そうでない場合は None を返します。<br/> 読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/zoomframe/slide/) | 形状の親スライドを返します。<br/> 読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/zoomframe/presentation/) | スライドの親プレゼンテーションを返します。<br/> 読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/zoomframe/graphical_object_lock/) | 形状のロック状態を返します。<br/> 読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`image_type`](/slides/python-net/ja/aspose.slides/zoomframe/image_type/) | ズーム オブジェクトの画像タイプを取得または設定します。<br/> 読み取り/書き込み [`ZoomImageType`](/slides/python-net/ja/aspose.slides/zoomimagetype)。<br/> デフォルト値: Preview |
| [`return_to_parent`](/slides/python-net/ja/aspose.slides/zoomframe/return_to_parent/) | スライドショー時のナビゲーション動作を取得または設定します。<br/> 読み取り/書き込み **bool**。<br/> デフォルト値: false |
| [`show_background`](/slides/python-net/ja/aspose.slides/zoomframe/show_background/) | ズームが対象スライドの背景を使用するかどうかを指定する値を取得または設定します。<br/> 読み取り/書き込み **bool**。<br/> デフォルト値: true |
| [`zoom_image`](/slides/python-net/ja/aspose.slides/zoomframe/zoom_image/) | ズーム オブジェクトの画像を取得または設定します。<br/> 読み取り/書き込み [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)。 |
| [`transition_duration`](/slides/python-net/ja/aspose.slides/zoomframe/transition_duration/) | ズームとスライド間のトランジションの期間を取得または設定します。<br/> 読み取り/書き込み **float**。<br/> デフォルト値: 1.0f |
| [`target_slide`](/slides/python-net/ja/aspose.slides/zoomframe/target_slide/) | Slide Zoom オブジェクトがリンクするスライドオブジェクトを取得または設定します。<br/> 読み取り/書き込み [`ISlide`](/slides/python-net/ja/aspose.slides/islide)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/zoomframe/get_image/#) | 形状のサムネイルを返します。<br/> デフォルトで ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | 形状のサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | 形状の内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 形状の内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/zoomframe/remove_placeholder/#) | この形状がプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | プレースホルダーが無い場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/zoomframe/get_base_placeholder/#) | 基本的なプレースホルダー形状（現在の形状が継承元となるレイアウトやマスタースライドからの形状）を返します。<br/> 継承元が無い場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/zoomframe/get_visual_bounds/#) | レンダリングされたコンテンツから計算された形状の視覚的境界を取得します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`ZoomFrame`](/slides/python-net/ja/aspose.slides/zoomframe)
* クラス [`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)