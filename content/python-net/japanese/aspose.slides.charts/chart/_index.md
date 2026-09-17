---
title: Chart class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chart/
---
## Chart クラス

スライド上のグラフィックチャートを表します。

**継承:**[`Chart`](/slides/python-net/ja/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ja/aspose.slides/shape)

Chart 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ja/aspose.slides.charts/chart/is_text_holder/) | shapeが TextHolder_PPT であるかどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`placeholder`](/slides/python-net/ja/aspose.slides.charts/chart/placeholder/) | shapeのプレースホルダーを返します。shapeにプレースホルダーがない場合は None を返します。<br/>            読み取り専用 [`IPlaceholder`](/slides/python-net/ja/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ja/aspose.slides.charts/chart/custom_data/) | shapeのカスタムデータを返します。<br/>            読み取り専用 [`ICustomData`](/slides/python-net/ja/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ja/aspose.slides.charts/chart/raw_frame/) | 生の shape フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ja/aspose.slides.charts/chart/frame/) | shape フレームのプロパティを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ja/aspose.slides.charts/chart/line_format/) | shape の線書式プロパティを含む LineFormat オブジェクトを返します。<br/>            注: 線プロパティを持たない特定の形状の場合、None を返すことがあります。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ja/aspose.slides.charts/chart/three_d_format/) | shape の 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。<br/>            注: 3D プロパティを持たない特定の形状の場合、None を返すことがあります。<br/>            読み取り専用 [`IThreeDFormat`](/slides/python-net/ja/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides.charts/chart/effect_format/) | shape に適用されたピクセル効果を含む EffectFormat オブジェクトを返します。<br/>            注: エフェクトプロパティを持たない特定の形状の場合、None を返すことがあります。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides.charts/chart/fill_format/) | shape の塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: 塗りつぶしプロパティを持たない特定の形状の場合、None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides.charts/chart/hyperlink_click/) | マウスクリック時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides.charts/chart/hyperlink_mouse_over/) | マウスオーバー時に定義されたハイパーリンクを取得または設定します。<br/>            読み書き [`IHyperlink`](/slides/python-net/ja/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides.charts/chart/hyperlink_manager/) | ハイパーリンクマネージャーを返します。<br/>            読み取り専用 [`IHyperlinkManager`](/slides/python-net/ja/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ja/aspose.slides.charts/chart/hidden/) | shape が非表示かどうかを判定します。<br/>            読み書き **bool**. |
| [`z_order_position`](/slides/python-net/ja/aspose.slides.charts/chart/z_order_position/) | z オーダー内での shape の位置を返します。Shapes[0] は z オーダーの背面にある shape を返し、Shapes[Shapes.Count - 1] は前面にある shape を返します。<br/>            読み取り専用 **int**. |
| [`connection_site_count`](/slides/python-net/ja/aspose.slides.charts/chart/connection_site_count/) | shape 上の接続ポイントの数を返します。<br/>            読み取り専用 **int**. |
| [`rotation`](/slides/python-net/ja/aspose.slides.charts/chart/rotation/) | 指定された shape が z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。<br/>            読み書き **float**. |
| [`x`](/slides/python-net/ja/aspose.slides.charts/chart/x/) | shape の左上隅の X 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`y`](/slides/python-net/ja/aspose.slides.charts/chart/y/) | shape の左上隅の Y 座標（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`width`](/slides/python-net/ja/aspose.slides.charts/chart/width/) | shape の幅（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`height`](/slides/python-net/ja/aspose.slides.charts/chart/height/) | shape の高さ（ポイント単位）を取得または設定します。<br/>            読み書き **float**. |
| [`black_white_mode`](/slides/python-net/ja/aspose.slides.charts/chart/black_white_mode/) | shape が白黒表示モードでどのように描画されるかを指定します。<br/>            読み書き [`BlackWhiteMode`](/slides/python-net/ja/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ja/aspose.slides.charts/chart/unique_id/) | アドインやその他のコードが使用することを想定した、プレゼンテーション スコープの内部識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能であり、永続的な一意キーとして扱ってはいけません。<br/>            読み取り専用 **int**.<br/>            参照 [`Shape.office_interop_shape_id`](/slides/python-net/ja/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ja/aspose.slides.charts/chart/office_interop_shape_id/) | スライドスコープの一意識別子を返します。この識別子は shape の寿命全体で一定であり、PowerPoint やインタープコードがドキュメント内の任意の場所から shape を確実に参照できます。<br/>            読み取り専用 **int**.<br/>            参照 [`Shape.unique_id`](/slides/python-net/ja/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ja/aspose.slides.charts/chart/alternative_text/) | shape に関連付けられた代替テキストを取得または設定します。<br/>            読み書き **str**. |
| [`alternative_text_title`](/slides/python-net/ja/aspose.slides.charts/chart/alternative_text_title/) | shape に関連付けられた代替テキストのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`name`](/slides/python-net/ja/aspose.slides.charts/chart/name/) | shape の名前を取得または設定します。None であってはなりません。必要に応じて空文字列を使用してください。<br/>            読み書き **str**. |
| [`is_decorative`](/slides/python-net/ja/aspose.slides.charts/chart/is_decorative/) | 「装飾としてマーク」オプションを取得または設定します。<br/>            読み書き **bool**. |
| [`shape_lock`](/slides/python-net/ja/aspose.slides.charts/chart/shape_lock/) | shape のロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ja/aspose.slides.charts/chart/is_grouped/) | shape がグループ化されているかどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`parent_group`](/slides/python-net/ja/aspose.slides.charts/chart/parent_group/) | shape がグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は None を返します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/chart/slide/) | shape の親スライドを返します。<br/>            読み取り専用 [`IBaseSlide`](/slides/python-net/ja/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/chart/presentation/) | スライドの親プレゼンテーションを返します。<br/>            読み取り専用 [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ja/aspose.slides.charts/chart/graphical_object_lock/) | shape のロック状態を返します。<br/>            読み取り専用 [`IGraphicalObjectLock`](/slides/python-net/ja/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/ja/aspose.slides.charts/chart/plot_visible_cells_only/) | 表示されるセルのみがプロットされるかどうかを判定します。False に設定すると、表示セルと非表示セルの両方がプロットされます。<br/>            読み書き **bool**. |
| [`display_blanks_as`](/slides/python-net/ja/aspose.slides.charts/chart/display_blanks_as/) | チャートで空白セルをプロットする方法を取得または設定します。<br/>            読み書き [`DisplayBlanksAsType`](/slides/python-net/ja/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/ja/aspose.slides.charts/chart/chart_data/) | チャートに関連付けられたリンク済みまたは埋め込みデータに関する情報を返します。<br/>            読み取り専用 [`IChartData`](/slides/python-net/ja/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/ja/aspose.slides.charts/chart/has_title/) | チャートに表示可能なタイトルがあるかどうかを判定します。<br/>            読み書き **bool**. |
| [`chart_title`](/slides/python-net/ja/aspose.slides.charts/chart/chart_title/) | チャートのタイトルを取得または設定します。<br/>            読み取り専用 [`IChartTitle`](/slides/python-net/ja/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/ja/aspose.slides.charts/chart/has_data_table/) | チャートにデータテーブルがあるかどうかを判定します。<br/>            読み書き **bool**. |
| [`has_legend`](/slides/python-net/ja/aspose.slides.charts/chart/has_legend/) | チャートに凡例があるかどうかを判定します。<br/>            読み書き **bool**. |
| [`legend`](/slides/python-net/ja/aspose.slides.charts/chart/legend/) | チャートの凡例を取得または設定します。<br/>            読み取り専用 [`ILegend`](/slides/python-net/ja/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/ja/aspose.slides.charts/chart/chart_data_table/) | チャートのデータテーブルを返します。<br/>            読み取り専用 [`IDataTable`](/slides/python-net/ja/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/ja/aspose.slides.charts/chart/style/) | チャートのスタイルを取得または設定します。<br/>            読み書き [`StyleType`](/slides/python-net/ja/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/ja/aspose.slides.charts/chart/type/) | チャートの種類を取得または設定します。<br/>            読み書き [`ChartType`](/slides/python-net/ja/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/ja/aspose.slides.charts/chart/plot_area/) | チャートのプロット領域を表します。<br/>            読み取り専用 [`IChartPlotArea`](/slides/python-net/ja/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/ja/aspose.slides.charts/chart/rotation_3d/) | チャートの 3D 回転を返します。<br/>            読み取り専用 [`IRotation3D`](/slides/python-net/ja/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/ja/aspose.slides.charts/chart/back_wall/) | 3D チャートの背面壁の書式を変更できるオブジェクトを返します。<br/>            読み取り専用 [`IChartWall`](/slides/python-net/ja/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/ja/aspose.slides.charts/chart/side_wall/) | 3D チャートの側面壁の書式を変更できるオブジェクトを返します。<br/>            読み取り専用 [`IChartWall`](/slides/python-net/ja/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/ja/aspose.slides.charts/chart/floor/) | 3D チャートの床面の書式を変更できるオブジェクトを返します。<br/>            読み取り専用 [`IChartWall`](/slides/python-net/ja/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/chart/text_format/) | チャートのテキスト書式を返します。次のタイプには適用できません: [`ChartType.TREEMAP`](/slides/python-net/ja/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/ja/aspose.slides.charts/charttype/SUNBURST), [`ChartType.WATERFALL`](/slides/python-net/ja/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/ja/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/ja/aspose.slides.charts/charttype/FUNNEL), [`ChartType.BOX_AND_WHISKER`](/slides/python-net/ja/aspose.slides.charts/charttype/BOX_AND_WHISKER)。<br/>            読み取り専用 [`IChartTextFormat`](/slides/python-net/ja/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/ja/aspose.slides.charts/chart/theme_manager/) | テーママネージャーを返します。<br/>            読み取り専用 [`IOverrideThemeManager`](/slides/python-net/ja/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/ja/aspose.slides.charts/chart/user_shapes/) | チャートの上に描画される shape を指定します。<br/>            読み取り専用 [`IGroupShape`](/slides/python-net/ja/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/ja/aspose.slides.charts/chart/axes/) | チャートの軸へのアクセスを提供します。<br/>            読み取り専用 [`IAxesManager`](/slides/python-net/ja/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/ja/aspose.slides.charts/chart/show_data_labels_over_maximum/) | チャートの最大値上に表示するデータラベルを指定します。<br/>            読み書き **bool**. |
| [`has_rounded_corners`](/slides/python-net/ja/aspose.slides.charts/chart/has_rounded_corners/) | チャート領域に丸みを帯びた角を設定するかどうかを指定します。<br/>            読み書き **bool**. |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/chart/chart/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides.charts/chart/get_image/#) | shape のサムネイルを返します。<br/>            デフォルトで ShapeThumbnailBounds.Shape の形状サムネイル境界タイプが使用されます。 |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | shape のサムネイルを返します。 |
| [`write_as_svg(self, stream)`](/slides/python-net/ja/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Shape の内容を SVG ファイルとして保存します。 |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ja/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape の内容を SVG ファイルとして保存します。 |
| [`remove_placeholder(self)`](/slides/python-net/ja/aspose.slides.charts/chart/remove_placeholder/#) | この shape がプレースホルダーではないことを定義します。 |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ja/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | プレースホルダーがない場合は新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [`get_base_placeholder(self)`](/slides/python-net/ja/aspose.slides.charts/chart/get_base_placeholder/#) | 基本的なプレースホルダー shape を返します（現在の shape が継承元となるレイアウトまたはマスタースライドからの shape）。<br/>            現在の shape が継承されていない場合は None が返されます。 |
| [`get_visual_bounds(self)`](/slides/python-net/ja/aspose.slides.charts/chart/get_visual_bounds/#) | 描画されたコンテンツから計算された shape の視覚的境界を取得します。 |
| [`validate_chart_layout(self)`](/slides/python-net/ja/aspose.slides.charts/chart/validate_chart_layout/#) | チャート要素の実際の値を計算します。実際の値には IActualLayout インターフェイスを実装する要素の位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) と実際の軸値 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) が含まれます。 |
| [`create_theme_effective(self)`](/slides/python-net/ja/aspose.slides.charts/chart/create_theme_effective/#) | このチャートに対する有効なテーマを返します。 |

### 参照
* クラス [`Chart`](/slides/python-net/ja/aspose.slides.charts/chart)
* クラス [`GraphicalObject`](/slides/python-net/ja/aspose.slides/graphicalobject)
* クラス [`Shape`](/slides/python-net/ja/aspose.slides/shape)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)