---
title: Ink class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/ink/
---
## Ink クラス

スライド上のインク オブジェクトを表します。

**継承:**[`Ink`](/slides/python-net/ja/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

Ink 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides.ink/ink/is_text_holder/) | シェイプが TextHolder_PPT であるかどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides.ink/ink/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides.ink/ink/custom_data/) | シェイプのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides.ink/ink/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides.ink/ink/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides.ink/ink/line_format/) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティがない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides.ink/ink/three_d_format/) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティがない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides.ink/ink/effect_format/) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティがない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides.ink/ink/fill_format/) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティがない特定のシェイプタイプでは None が返されることがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides.ink/ink/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides.ink/ink/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides.ink/ink/hyperlink_manager/) | ハイパーリンク マネージャを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides.ink/ink/hidden/) | シェイプが非表示かどうかを判定します。<br/>            読み書き可能 **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides.ink/ink/z_order_position/) | z オーダーにおけるシェイプの位置を返します。<br/>            Shapes[0] は z オーダーの背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides.ink/ink/connection_site_count/) | シェイプ上の接続点の数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides.ink/ink/rotation/) | 指定されたシェイプが z 軸を中心に回転する角度（度数）を取得または設定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。<br/>            読み書き可能 **float**. |
| [`x`](/slides/python-net/ja/aspose.slides.ink/ink/x/) | シェイプの左上隅の x 座標をポイント単位で取得または設定します。<br/>            読み書き可能 **float**. |
| [`y`](/slides/python-net/ja/aspose.slides.ink/ink/y/) | シェイプの左上隅の y 座標をポイント単位で取得または設定します。<br/>            読み書き可能 **float**. |
| [`width`](/slides/python-net/ja/aspose.slides.ink/ink/width/) | シェイプの幅をポイント単位で取得または設定します。<br/>            読み書き可能 **float**. |
| [`height`](/slides/python-net/ja/aspose.slides.ink/ink/height/) | シェイプの高さをポイント単位で取得または設定します。<br/>            読み書き可能 **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides.ink/ink/black_white_mode/) | シェイプが白黒表示モードでどのようにレンダリングされるかを指定するプロパティです。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides.ink/ink/unique_id/) | アドインやその他のコードで使用することを意図した、内部のプレゼンテーション スコープの識別子を返します。<br/>            この値はユーザーやプログラムにより再割り当て可能なため、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**。<br/>            詳細は [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id) を参照してください。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides.ink/ink/office_interop_shape_id/) | シェイプの存続期間中一定であり、ドキュメント内の任意の場所から PowerPoint または interop コードがシェイプを確実に参照できるようにする、スライドスコープの一意識別子を返します。<br/>            読み取り専用 **int**。<br/>            詳細は [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id) を参照してください。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides.ink/ink/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides.ink/ink/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**. |
| [`name`](/slides/python-net/ja/aspose.slides.ink/ink/name/) | シェイプの名前を取得または設定します。<br/>            None ではいけません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides.ink/ink/is_decorative/) | '装飾としてマーク' オプションを取得または設定します<br/>            読み書き可能 **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides.ink/ink/shape_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides.ink/ink/is_grouped/) | シェイプがグループ化されているかどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides.ink/ink/parent_group/) | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides.ink/ink/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides.ink/ink/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides.ink/ink/graphical_object_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/ja/aspose.slides.ink/ink/traces/) | IInk 要素 [`IInkTrace`](/slides/python-net/ja/aspose.slides.ink/iinktrace) に含まれるすべてのトレースを取得します。<br/>            読み取り専用. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides.ink/ink/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | シェイプのコンテンツを SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプのコンテンツを SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides.ink/ink/remove_placeholder/#) | このシェイプがプレースホルダーでないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定したものにプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides.ink/ink/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides.ink/ink/get_visual_bounds/#) | シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。 |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/ja/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションに画像を登録します。<br/>            これらの画像は特定の [`InkEffectType`](/slides/python-net/ja/aspose.slides.ink/inkeffecttype) 値でインクをレンダリングする際に使用されます。<br/>            例えば Galaxy、Rainbow などです。独自の画像を提供することで、各インク効果の表示方法を制御できます。 |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/ja/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションから画像の登録を解除します。<br/>            以前に **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide** を使用して登録された画像です。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Ink`](/slides/python-net/ja/aspose.slides.ink/ink)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)