---
title: SummaryZoomSection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection クラス

SummaryZoom フレーム内の Summary Zoom Section オブジェクトを表します。

**Inheritance:**[`SummaryZoomSection`](/slides/python-net/ja/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/ja/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

SummaryZoomSection 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/summaryzoomsection/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides/summaryzoomsection/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/summaryzoomsection/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/summaryzoomsection/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides/summaryzoomsection/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides/summaryzoomsection/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: can return None for certain types of shapes which don't have line properties.<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/summaryzoomsection/three_d_format/) | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: can return None for certain types of shapes which don't have 3d properties.<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/summaryzoomsection/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: can return None for certain types of shapes which don't have effect properties.<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/summaryzoomsection/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: can return None for certain types of shapes which don't have fill properties.<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/summaryzoomsection/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/summaryzoomsection/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides/summaryzoomsection/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/summaryzoomsection/z_order_position/) | Z 順序におけるシェイプの位置を返します。<br/>            Shapes[0] は Z 順序の背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/summaryzoomsection/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides/summaryzoomsection/rotation/) | 指定されたシェイプが Z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを表します。<br/>            読み書き **float**. |
| [`x`](/slides/python-net/ja/aspose.slides/summaryzoomsection/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/summaryzoomsection/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/summaryzoomsection/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/summaryzoomsection/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/summaryzoomsection/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides/summaryzoomsection/unique_id/) | アドインやその他のコードで使用することを想定した、プレゼンテーションスコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムにより再割り当て可能なため、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**.<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/summaryzoomsection/office_interop_shape_id/) | シェイプの有効期間中一定で、スライドスコープの一意識別子を返します。PowerPoint やインターオップコードがドキュメント内の任意の場所からシェイプを確実に参照できます。<br/>            読み取り専用 **int**.<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/summaryzoomsection/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/summaryzoomsection/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`name`](/slides/python-net/ja/aspose.slides/summaryzoomsection/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/summaryzoomsection/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/summaryzoomsection/shape_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/summaryzoomsection/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides/summaryzoomsection/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides/summaryzoomsection/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides/summaryzoomsection/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/summaryzoomsection/graphical_object_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/ja/aspose.slides/summaryzoomsection/image_type/) | ズームオブジェクトの画像タイプを取得または設定します。<br/>            読み書き [`ZoomImageType`](/slides/python-net/ja/aspose.slides/zoomimagetype).<br/>            デフォルト値: Preview |
| [`return_to_parent`](/slides/python-net/ja/aspose.slides/summaryzoomsection/return_to_parent/) | スライドショー中のナビゲーション動作を取得または設定します。<br/>            読み書き **bool**.<br/>            デフォルト値: false |
| [`show_background`](/slides/python-net/ja/aspose.slides/summaryzoomsection/show_background/) | ズームが目的スライドの背景を使用するかどうかを指定する値を取得または設定します。<br/>            読み書き **bool**.<br/>            デフォルト値: true |
| [`zoom_image`](/slides/python-net/ja/aspose.slides/summaryzoomsection/zoom_image/) | ズームオブジェクトの画像を取得または設定します。<br/>            読み書き [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/ja/aspose.slides/summaryzoomsection/transition_duration/) | ズームとスライド間の遷移時間を取得または設定します。<br/>            読み書き **float**.<br/>            デフォルト値: 1.0f |
| [`target_section`](/slides/python-net/ja/aspose.slides/summaryzoomsection/target_section/) | Section Zoom オブジェクトがリンクするセクションオブジェクトを取得または設定します。<br/>            読み書き [`ISection`](/slides/python-net/ja/aspose.slides/isection). |
| [`title`](/slides/python-net/ja/aspose.slides/summaryzoomsection/title/) | Summary Zoom Section オブジェクトのテキストタイトルを返します。 |
| [`description`](/slides/python-net/ja/aspose.slides/summaryzoomsection/description/) | Summary Zoom Section オブジェクトのテキスト説明を返します。 |

## メソッド

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/get_image/#) | シェイプサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape シェイプサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | シェイプサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Shape の内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape の内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（レイアウトまたはマスタースライドから継承されたシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/summaryzoomsection/get_visual_bounds/#) | シェイプの描画されたコンテンツから計算された視覚的境界を取得します。 |

### 参照
* class [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* class [`SectionZoomFrame`](/slides/python-net/ja/aspose.slides/sectionzoomframe)
* class [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* class [`SummaryZoomSection`](/slides/python-net/ja/aspose.slides/summaryzoomsection)
* class [`ZoomObject`](/slides/python-net/ja/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)