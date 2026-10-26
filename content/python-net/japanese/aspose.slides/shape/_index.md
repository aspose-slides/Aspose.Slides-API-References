---
title: Shape class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/shape/
---
## Shape クラス

スライド上のシェイプを表します。

Shape 型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/shape/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/shape/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/shape/custom_data/) | シェイプのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/shape/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/shape/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/shape/line_format/) | シェイプの線フォーマット プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/shape/three_d_format/) | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/shape/effect_format/) | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/shape/fill_format/) | シェイプの塗りつぶしフォーマット プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/shape/hyperlink_click/) | マウスクリック時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/shape/hyperlink_mouse_over/) | マウスオーバー時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/shape/hyperlink_manager/) | ハイパーリンク マネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/shape/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/shape/z_order_position/) | シェイプの Z 順序での位置を返します。<br/>            Shapes[0] は Z 順序の最背面のシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面のシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/shape/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/shape/rotation/) | 指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。<br/>            正の値は時計回り、負の値は反時計回りを示します。<br/>            読み書き可能 **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/shape/x/) | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/shape/y/) | シェイプの左上隅の Y座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/shape/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/shape/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/shape/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id/) | アドインやその他のコードで使用することを意図した、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムにより再割り当て可能なため、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**。<br/>            詳細は [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id) を参照してください。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id/) | シェイプの存続期間中一定で、スライド スコープの一意識別子を返します。これにより PowerPoint やインターオップ コードがドキュメント内の任意の場所からシェイプを確実に参照できます。<br/>            読み取り専用 **int**。<br/>            詳細は [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id) を参照してください。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/shape/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/shape/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/shape/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/shape/is_decorative/) | '装飾としてマーク' オプションを取得または設定します。<br/>            読み書き可能 **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/shape/shape_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IBaseShapeLock`](/slides/python-net/ja/aspose.slides/ibaseshapelock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/shape/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/shape/parent_group/) | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。グループ化されていない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/shape/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/shape/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |

## メソッド

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/shape/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape がサムネイルの境界タイプとして使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/shape/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/shape/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/shape/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたものにプレースホルダー プロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/shape/get_base_placeholder/#) | 基本的なプレースホルダー シェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。<br/>            継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/shape/get_visual_bounds/#) | シェイプの描画内容から計算された視覚的境界を取得します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)