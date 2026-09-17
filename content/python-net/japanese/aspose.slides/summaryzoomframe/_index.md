---
title: SummaryZoomFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame クラス

スライド内の Summary Zoom オブジェクトを表します。

**継承:**[`SummaryZoomFrame`](/slides/python-net/ja/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

SummaryZoomFrame タイプは次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/summaryzoomframe/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/summaryzoomframe/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/summaryzoomframe/custom_data/) | シェイプのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/summaryzoomframe/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/summaryzoomframe/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/summaryzoomframe/line_format/) | シェイプのライン書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: ライン プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/summaryzoomframe/three_d_format/) | シェイプの 3D エフェクト プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/summaryzoomframe/effect_format/) | シェイプに適用されたピクセル エフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクト プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/summaryzoomframe/fill_format/) | シェイプの塗り書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗り プロパティを持たない特定のシェイプタイプでは None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/summaryzoomframe/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/summaryzoomframe/hyperlink_manager/) | ハイパーリンク マネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/summaryzoomframe/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/summaryzoomframe/z_order_position/) | シェイプの Z 順序における位置を返します。<br/>            Shapes[0] は Z 順序の最背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/summaryzoomframe/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/summaryzoomframe/rotation/) | 指定されたシェイプが Z 軸周りに回転する角度（度）を取得または設定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。<br/>            読み書き **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/summaryzoomframe/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/summaryzoomframe/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/summaryzoomframe/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/summaryzoomframe/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/summaryzoomframe/black_white_mode/) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/summaryzoomframe/unique_id/) | アドインや他のコードが使用することを意図した、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/summaryzoomframe/office_interop_shape_id/) | シェイプの存続期間中に一定で、PowerPoint やインターオップ コードがドキュメント内の任意の場所からシェイプを確実に参照できるスライド スコープの一意識別子を返します。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/summaryzoomframe/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/summaryzoomframe/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/summaryzoomframe/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/summaryzoomframe/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/summaryzoomframe/shape_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/summaryzoomframe/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/summaryzoomframe/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。それ以外の場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/summaryzoomframe/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/summaryzoomframe/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/summaryzoomframe/graphical_object_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`layout`](/slides/python-net/ja/aspose.slides/summaryzoomframe/layout/) | フレーム内の Summary Zoom セクションのレイアウトを取得します。<br/>            デフォルト値は GridLayout です。 |
| [`summary_zoom_collection`](/slides/python-net/ja/aspose.slides/summaryzoomframe/summary_zoom_collection/) | Summary Zoom Frame オブジェクトの [`ISummaryZoomSectionCollection`](/slides/python-net/ja/aspose.slides/isummaryzoomsectioncollection) を取得します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/get_base_placeholder/#) | 基本的なプレースホルダー シェイプ（現在のシェイプが継承しているレイアウトやマスタースライドからのシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/summaryzoomframe/get_visual_bounds/#) | シェイプのレンダリングされた内容から算出された視覚的境界を取得します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* クラス [`SummaryZoomFrame`](/slides/python-net/ja/aspose.slides/summaryzoomframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)