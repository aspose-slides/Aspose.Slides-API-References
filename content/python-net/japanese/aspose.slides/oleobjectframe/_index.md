---
title: OleObjectFrame class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/oleobjectframe/
---
## OleObjectFrame クラス

スライド上の OLE オブジェクトを表します。

**Inheritance:**[`OleObjectFrame`](/slides/python-net/ja/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

OleObjectFrame 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides/oleobjectframe/is_text_holder/) | シェイプが TextHolder_PPT かどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`placeholder`](/slides/python-net/ja/aspose.slides/oleobjectframe/placeholder/) | シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder)。 |
| [`custom_data`](/slides/python-net/ja/aspose.slides/oleobjectframe/custom_data/) | シェイプのカスタム データを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata)。 |
| [`raw_frame`](/slides/python-net/ja/aspose.slides/oleobjectframe/raw_frame/) | 生のシェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/oleobjectframe/frame/) | シェイプ フレームのプロパティを取得または設定します。<br/>            読み書き可能 [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`line_format`](/slides/python-net/ja/aspose.slides/oleobjectframe/line_format/) | シェイプの線の書式設定プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat)。 |
| [`three_d_format`](/slides/python-net/ja/aspose.slides/oleobjectframe/three_d_format/) | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat)。 |
| [`effect_format`](/slides/python-net/ja/aspose.slides/oleobjectframe/effect_format/) | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/>            注: 効果プロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat)。 |
| [`fill_format`](/slides/python-net/ja/aspose.slides/oleobjectframe/fill_format/) | シェイプの塗りつぶし書式設定プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定の種類のシェイプの場合、None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/oleobjectframe/hyperlink_click/) | マウスクリック用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。<br/>            読み書き可能 [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink)。 |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/oleobjectframe/hyperlink_manager/) | ハイパーリンク マネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager)。 |
| [`hidden`](/slides/python-net/ja/aspose.slides/oleobjectframe/hidden/) | シェイプが非表示かどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`z_order_position`](/slides/python-net/ja/aspose.slides/oleobjectframe/z_order_position/) | シェイプの Z オーダー内での位置を返します。<br/>            Shapes[0] は Z オーダーの最背面にあるシェイプを返し、<br/>            Shapes[Shapes.Count - 1] は最前面にあるシェイプを返します。<br/>            読み取り専用 **int**。 |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides/oleobjectframe/connection_site_count/) | シェイプ上の接続ポイントの数を返します。<br/>            読み取り専用 **int**。 |
| [`rotation`](/slides/python-net/ja/aspose.slides/oleobjectframe/rotation/) | 指定されたシェイプが Z 軸周りに回転する角度（度）を取得または設定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。<br/>            読み書き可能 **float**。 |
| [`x`](/slides/python-net/ja/aspose.slides/oleobjectframe/x/) | シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides/oleobjectframe/y/) | シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides/oleobjectframe/width/) | シェイプの幅（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides/oleobjectframe/height/) | シェイプの高さ（ポイント単位）を取得または設定します。<br/>            読み書き可能 **float**。 |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides/oleobjectframe/black_white_mode/) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。<br/>            読み書き可能 [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode)。 |
| [`unique_id`](/slides/python-net/ja/aspose.slides/oleobjectframe/unique_id/) | アドインやその他のコードで使用されることを想定した、プレゼンテーション スコープの内部識別子を返します。<br/>            この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id)。 |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides/oleobjectframe/office_interop_shape_id/) | スライド スコープの一意識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint やインターオップ コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。<br/>            読み取り専用 **int**。<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id)。 |
| [`alternative_text`](/slides/python-net/ja/aspose.slides/oleobjectframe/alternative_text/) | シェイプに関連付けられた代替テキストを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides/oleobjectframe/alternative_text_title/) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`name`](/slides/python-net/ja/aspose.slides/oleobjectframe/name/) | シェイプの名前を取得または設定します。<br/>            None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き可能 **str**。 |
| [`is_decorative`](/slides/python-net/ja/aspose.slides/oleobjectframe/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き可能 **bool**。 |
| [`shape_lock`](/slides/python-net/ja/aspose.slides/oleobjectframe/shape_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`is_grouped`](/slides/python-net/ja/aspose.slides/oleobjectframe/is_grouped/) | シェイプがグループ化されているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`parent_group`](/slides/python-net/ja/aspose.slides/oleobjectframe/parent_group/) | シェイプがグループ化されている場合、親の GroupShape オブジェクトを返します。そうでなければ None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape)。 |
| [`slide`](/slides/python-net/ja/aspose.slides/oleobjectframe/slide/) | シェイプの親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide)。 |
| [`presentation`](/slides/python-net/ja/aspose.slides/oleobjectframe/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)。 |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides/oleobjectframe/graphical_object_lock/) | シェイプのロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock)。 |
| [`substitute_picture_format`](/slides/python-net/ja/aspose.slides/oleobjectframe/substitute_picture_format/) | OleObject の画像塗りつぶしプロパティ オブジェクトを返します。<br/>            読み取り専用 [`IPictureFillFormat`](/slides/python-net/ja/aspose.slides/ipicturefillformat)。 |
| [`substitute_picture_title`](/slides/python-net/ja/aspose.slides/oleobjectframe/substitute_picture_title/) | OleObject アイコンのタイトルを取得または設定します。<br/>            読み書き可能 **str**。 |
| [`object_name`](/slides/python-net/ja/aspose.slides/oleobjectframe/object_name/) | オブジェクトの名前を取得または設定します。<br/>            読み書き可能 **str**。 |
| [`object_prog_id`](/slides/python-net/ja/aspose.slides/oleobjectframe/object_prog_id/) | オブジェクトの ProgID を返します。<br/>            読み取り専用 **str**。 |
| [`link_file_name`](/slides/python-net/ja/aspose.slides/oleobjectframe/link_file_name/) | リンクされたファイルへのフルパスを返します。短いファイル名が使用されます。<br/>            読み取り専用 **str**。 |
| [`link_path_long`](/slides/python-net/ja/aspose.slides/oleobjectframe/link_path_long/) | リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。<br/>            読み書き可能 **str**。 |
| [`link_path_relative`](/slides/python-net/ja/aspose.slides/oleobjectframe/link_path_relative/) | リンクされたファイルが存在する場合は相対パスを返し、存在しない場合は空文字列を返します。<br/>            読み取り専用 **str**。 |
| [`embedded_file_label`](/slides/python-net/ja/aspose.slides/oleobjectframe/embedded_file_label/) | 埋め込み OLE オブジェクトのファイル名を返します |
| [`embedded_file_name`](/slides/python-net/ja/aspose.slides/oleobjectframe/embedded_file_name/) | 埋め込み OLE オブジェクトのパスを返します |
| [`embedded_data`](/slides/python-net/ja/aspose.slides/oleobjectframe/embedded_data/) | OLE 埋め込みデータに関する情報を取得または設定します。<br/>            読み書き可能 [`IOleEmbeddedDataInfo`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo)。 |
| [`is_object_icon`](/slides/python-net/ja/aspose.slides/oleobjectframe/is_object_icon/) | オブジェクトがアイコンとして表示されるかどうかを判断します。<br/>            読み書き可能 **bool**。 |
| [`is_object_link`](/slides/python-net/ja/aspose.slides/oleobjectframe/is_object_link/) | オブジェクトが外部ファイルにリンクされているかどうかを判断します。<br/>            読み取り専用 **bool**。 |
| [`update_automatic`](/slides/python-net/ja/aspose.slides/oleobjectframe/update_automatic/) | プレゼンテーションが開かれたり印刷されたりしたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判断します。<br/>            読み書き可能 **bool**。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/oleobjectframe/get_image/#) | シェイプのサムネイルを返します。<br/>            デフォルトでは ShapeThumbnailBounds.Shape シェイプ サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | シェイプのサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | シェイプの内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | シェイプの内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides/oleobjectframe/remove_placeholder/#) | このシェイプがプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides/oleobjectframe/get_base_placeholder/#) | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。<br/>            現在のシェイプが継承されていない場合は None を返します。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides/oleobjectframe/get_visual_bounds/#) | シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。 |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/ja/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | OLE 埋め込みデータに関する情報を設定します。<br/>            <br/>            このメソッドはオブジェクトのプロパティを新しいデータに反映するように変更し、<br/>            IsObjectLink フラグを false に設定して、OLE オブジェクトが埋め込まれていることを示します。 |

### 参照
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`OleObjectFrame`](/slides/python-net/ja/aspose.slides/oleobjectframe)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)