---
title: LegacyDiagram class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/legacydiagram/
---
## LegacyDiagram クラス

レガシーダイアグラム オブジェクトを表します。

**継承:**[`LegacyDiagram`](/slides/python-net/ja/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

LegacyDiagram 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/legacydiagram/is_text_holder/) | シェイプが TextHolder_PPT かどうかを決定します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/legacydiagram/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/legacydiagram/custom_data/) | シェイプのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/legacydiagram/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/legacydiagram/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/legacydiagram/line_format/) | シェイプのライン 書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: ライン プロパティがない特定の種類のシェイプでは None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/legacydiagram/three_d_format/) | シェイプの 3D エフェクト プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティがない特定の種類のシェイプでは None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/legacydiagram/effect_format/) | シェイプに適用されたピクセル エフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクト プロパティがない特定の種類のシェイプでは None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/legacydiagram/fill_format/) | シェイプの塗りつぶし 書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶし プロパティがない特定の種類のシェイプでは None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/legacydiagram/hyperlink_click/) | マウス クリック時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/legacydiagram/hyperlink_mouse_over/) | マウス オーバー時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/legacydiagram/hyperlink_manager/) | ハイパーリンク マネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/legacydiagram/hidden/) | シェイプが非表示かどうかを決定します。<br/>            読み書き可能 **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/legacydiagram/z_order_position/) | シェイプの Z 順序における位置を返します。<br/>            Shapes[0] は Z 順序の最背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/legacydiagram/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/legacydiagram/rotation/) | 指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。<br/>            正の値は時計回り回転、負の値は反時計回り回転を示します。<br/>            読み書き可能 **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/legacydiagram/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/legacydiagram/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/legacydiagram/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/legacydiagram/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/legacydiagram/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/legacydiagram/unique_id/) | アドインやその他のコードで使用することを意図した、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/legacydiagram/office_interop_shape_id/) | シェイプの存続期間中一定であり、ドキュメント内の任意の場所から PowerPoint またはインタープコードがシェイプを確実に参照できる、スライド スコープの一意識別子を返します。<br/>            読み取り専用 **int**。<br/>            参照: [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/legacydiagram/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/legacydiagram/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/legacydiagram/name/) | シェイプの名前を取得または設定します。<br/>            None であってはならず、必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/legacydiagram/is_decorative/) | 装飾としてマーク (Mark as decorative) オプションを取得または設定します。<br/>            読み書き可能 **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/legacydiagram/shape_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/legacydiagram/is_grouped/) | シェイプがグループ化されているかどうかを決定します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/legacydiagram/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/legacydiagram/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/legacydiagram/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/legacydiagram/graphical_object_lock/) | シェイプのロックを返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/legacydiagram/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/legacydiagram/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/legacydiagram/get_base_placeholder/#) | 基本的なプレースホルダー シェイプ（現在のシェイプが継承されているレイアウトまたはマスタースライドからのシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/legacydiagram/get_visual_bounds/#) | シェイプのレンダリングされたコンテンツから計算された可視境界を取得します。 |
| [`convert_to_smart_art(self)`](/slides/python-net/ja/aspose.slides/legacydiagram/convert_to_smart_art/#) | レガシー ダイアグラムを編集可能な SmartArt オブジェクトに変換します。<br/>            作成された SmartArt オブジェクトは同じ位置の親グループシェイプに追加されます。 |
| [`convert_to_group_shape(self)`](/slides/python-net/ja/aspose.slides/legacydiagram/convert_to_group_shape/#) | レガシー ダイアグラムを編集可能なグループ シェイプに変換します。<br/>            作成された GroupShape オブジェクトは同じ位置の親グループシェイプに追加されます。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`LegacyDiagram`](/slides/python-net/ja/aspose.slides/legacydiagram)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)