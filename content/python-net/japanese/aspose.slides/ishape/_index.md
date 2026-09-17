---
title: IShape class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ishape/
---
## IShape クラス

Represents a shape on a slide.

The IShape type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/ishape/is_text_holder/) | シェイプが TextHolder かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/ishape/placeholder/) | シェイプのプレースホルダーを返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/ishape/custom_data/) | シェイプのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/ishape/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/ishape/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/ishape/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/ishape/three_d_format/) | シェイプの線書式プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/ishape/effect_format/) | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/ishape/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/ishape/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/ishape/z_order_position/) | シェイプの z オーダー内での位置を返します。<br/>            Shapes[0] は z オーダーの奥にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は z オーダーの手前にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/ishape/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/ishape/rotation/) | 指定されたシェイプが z 軸周りに回転する角度（度）を取得または設定します。<br/>            正の値は時計回りの回転、負の値は反時計回りの回転を表します。<br/>            読み書き **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/ishape/x/) | シェイプの左上隅の x 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/ishape/y/) | シェイプの左上隅の y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/ishape/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/ishape/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/ishape/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/ishape/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/ishape/name/) | シェイプの名前を取得または設定します。<br/>            読み書き **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/ishape/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/ishape/shape_lock/) | シェイプのロック情報を返します。<br/>            読み取り専用 [`IBaseShapeLock`](/slides/python-net/ja/aspose.slides/ibaseshapelock)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/ishape/unique_id/) | アドインやその他のコードで使用することを目的とした、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。<br/>            読み取り専用 **int**。<br/>            参照 [`IShape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/ishape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/ishape/office_interop_shape_id/) | スライド スコープの一意識別子を返します。この識別子はシェイプの存続期間中は変わらず、PowerPoint やインターオップ コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照 [`IShape.unique_id`](/slides/python-net/ja/aspose.slides/ishape/unique_id)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/ishape/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/ishape/black_white_mode/) | シェイプが白黒表示モードでどのようにレンダリングされるかを指定するプロパティです。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/ishape/parent_group/) | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/ishape/hyperlink_manager/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/ishape/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプ サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/ishape/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/ishape/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/ishape/remove_placeholder/#) | このシェイプがプレースホルダーでないことを定義します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/ishape/get_base_placeholder/#) | 基本的なプレースホルダー シェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドのシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None を返します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)