---
title: SectionZoomFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame クラス

スライド内の Section Zoom オブジェクトを表します。

**継承:**[`SectionZoomFrame`](/slides/python-net/ja/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

SectionZoomFrame 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/sectionzoomframe/is_text_holder/) | 形状が TextHolder_PPT かどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides/sectionzoomframe/placeholder/) | 形状のプレースホルダーを返します。形状にプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/sectionzoomframe/custom_data/) | 形状のカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/sectionzoomframe/raw_frame/) | 生の形状フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides/sectionzoomframe/frame/) | 形状フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides/sectionzoomframe/line_format/) | 形状の線フォーマット プロパティを含む LineFormat オブジェクトを返します。<br/>            注意: 線プロパティを持たない特定のタイプの形状では None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/sectionzoomframe/three_d_format/) | 形状の 3D エフェクト プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注意: 3D プロパティを持たない特定のタイプの形状では None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/sectionzoomframe/effect_format/) | 形状に適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/>            注意: 効果プロパティを持たない特定のタイプの形状では None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/sectionzoomframe/fill_format/) | 形状の塗りつぶしフォーマット プロパティを含む FillFormat オブジェクトを返します。<br/>            注意: 塗りつぶしプロパティを持たない特定のタイプの形状では None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/sectionzoomframe/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/sectionzoomframe/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides/sectionzoomframe/hidden/) | 形状が非表示かどうかを判定します。<br/>            読み書き **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/sectionzoomframe/z_order_position/) | z 順序における形状の位置を返します。<br/>            Shapes[0] は z 順序の背面にある形状を返し、<br/>            Shapes[Shapes.Count - 1] は最前面の形状を返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/sectionzoomframe/connection_site_count/) | 形状上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides/sectionzoomframe/rotation/) | 指定された形状が z 軸周りに回転する角度（度数）を取得または設定します。<br/>            正の値は時計回りの回転、負の値は反時計回りの回転を示します。<br/>            読み書き **float**. |
| [`x`](/slides/python-net/ja/aspose.slides/sectionzoomframe/x/) | 形状の左上隅の x 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/sectionzoomframe/y/) | 形状の左上隅の y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/sectionzoomframe/width/) | 形状の幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/sectionzoomframe/height/) | 形状の高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/sectionzoomframe/black_white_mode/) | プロパティは形状が白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides/sectionzoomframe/unique_id/) | アドインやその他のコードが使用することを意図した、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/sectionzoomframe/office_interop_shape_id/) | スライドスコープの一意識別子を返します。これは形状の存続期間中一定で、PowerPoint やインターオップ コードがドキュメント内の任意の場所から形状を確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/sectionzoomframe/alternative_text/) | 形状に関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/sectionzoomframe/alternative_text_title/) | 形状に関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`name`](/slides/python-net/ja/aspose.slides/sectionzoomframe/name/) | 形状の名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/sectionzoomframe/is_decorative/) | 装飾としてマークするオプションを取得または設定します。<br/>            読み書き **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/sectionzoomframe/shape_lock/) | 形状のロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/sectionzoomframe/is_grouped/) | 形状がグループ化されているかどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides/sectionzoomframe/parent_group/) | 形状がグループ化されている場合は親の GroupShape オブジェクトを返します。そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides/sectionzoomframe/slide/) | 形状の親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides/sectionzoomframe/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/sectionzoomframe/graphical_object_lock/) | 形状のロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ja/aspose.slides/sectionzoomframe/image_type/) | ズームオブジェクトの画像タイプを取得または設定します。<br/>            読み書き [`ZoomImageType`](/slides/python-net/ja/aspose.slides/zoomimagetype)。<br/>            デフォルト値: Preview |
| [`return_to_parent`](/slides/python-net/ja/aspose.slides/sectionzoomframe/return_to_parent/) | スライドショーでのナビゲーション動作を取得または設定します。<br/>            読み書き **bool**。<br/>            デフォルト値: false |
| [`show_background`](/slides/python-net/ja/aspose.slides/sectionzoomframe/show_background/) | ズームが目的スライドの背景を使用するかどうかを指定する値を取得または設定します。<br/>            読み書き **bool**。<br/>            デフォルト値: true |
| [`zoom_image`](/slides/python-net/ja/aspose.slides/sectionzoomframe/zoom_image/) | ズームオブジェクトの画像を取得または設定します。<br/>            読み書き [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ja/aspose.slides/sectionzoomframe/transition_duration/) | ズームとスライド間の遷移時間を取得または設定します。<br/>            読み書き **float**。<br/>            デフォルト値: 1.0f |
| [`target_section`](/slides/python-net/ja/aspose.slides/sectionzoomframe/target_section/) | Section Zoom オブジェクトがリンクするセクションオブジェクトを取得または設定します。<br/>            読み書き [`ISection`](/slides/python-net/ja/aspose.slides/isection). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/get_image/#) | 形状のサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape 形状サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | 形状のサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | Shape の内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape の内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/remove_placeholder/#) | この形状がプレースホルダーでないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/get_base_placeholder/#) | 基本的なプレースホルダー形状（現在の形状が継承元となるレイアウトまたはマスタースライドからの形状）を返します。<br/>            現在の形状が継承されていない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/sectionzoomframe/get_visual_bounds/#) | 形状のレンダリングされたコンテンツから計算されたビジュアル境界を取得します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`SectionZoomFrame`](/slides/python-net/ja/aspose.slides/sectionzoomframe)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)