---
title: GraphicalObject class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/graphicalobject/
---
## GraphicalObject クラス

抽象的なグラフィカルオブジェクトを表します。

**継承:**[`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

GraphicalObject 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/graphicalobject/is_text_holder/) | シェイプが TextHolder_PPT かどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides/graphicalobject/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides/graphicalobject/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/graphicalobject/raw_frame/) | 生のシェイプフレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides/graphicalobject/frame/) | シェイプフレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides/graphicalobject/line_format/) | シェイプの線の書式設定プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のタイプのシェイプでは None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/graphicalobject/three_d_format/) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のタイプのシェイプでは None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/graphicalobject/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のタイプのシェイプでは None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/graphicalobject/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のタイプのシェイプでは None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/graphicalobject/hyperlink_click/) | マウスクリックに定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/graphicalobject/hyperlink_mouse_over/) | マウスオーバーに定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/graphicalobject/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides/graphicalobject/hidden/) | シェイプが非表示かどうかを決定します。<br/>            読み書き可能 **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/graphicalobject/z_order_position/) | シェイプの Z 順序における位置を返します。<br/>            Shapes[0] は Z 順序の背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/graphicalobject/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides/graphicalobject/rotation/) | 指定したシェイプが Z 軸周りに回転する角度（度）を取得または設定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。<br/>            読み書き可能 **float**. |
| [`x`](/slides/python-net/ja/aspose.slides/graphicalobject/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`y`](/slides/python-net/ja/aspose.slides/graphicalobject/y/) | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`width`](/slides/python-net/ja/aspose.slides/graphicalobject/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`height`](/slides/python-net/ja/aspose.slides/graphicalobject/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/graphicalobject/black_white_mode/) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides/graphicalobject/unique_id/) | アドインやその他のコードで使用することを目的とした、プレゼンテーションスコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/graphicalobject/office_interop_shape_id/) | スライドスコープ内の一意識別子を返します。この識別子はシェイプの存続期間中は一定で、PowerPoint やインターオップコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/graphicalobject/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/graphicalobject/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**. |
| [`name`](/slides/python-net/ja/aspose.slides/graphicalobject/name/) | シェイプの名前を取得または設定します。<br/>            None ではあってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/graphicalobject/is_decorative/) | '装飾としてマーク' オプションを取得または設定します。<br/>            読み書き可能 **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/graphicalobject/shape_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/graphicalobject/is_grouped/) | シェイプがグループ化されているかどうかを決定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides/graphicalobject/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides/graphicalobject/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides/graphicalobject/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/graphicalobject/graphical_object_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/graphicalobject/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/graphicalobject/remove_placeholder/#) | このシェイプがプレースホルダーでないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/graphicalobject/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（現在のシェイプが継承元であるレイアウトやマスタースライドからのシェイプ）を返します。<br/>            継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/graphicalobject/get_visual_bounds/#) | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)