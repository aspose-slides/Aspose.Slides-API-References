---
title: Chart
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のグラフィックチャートを表します。
type: docs
weight: 53
url: /ja/aspose.slides.charts/chart/
---
## Chart クラス

Represents an graphic chart on a slide.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | プレースホルダーが存在しない場合は新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | このチャートに対する有効なテーマを返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 参照によってオブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | シェイプに関連付けられた代替テキストを返します。参照 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | シェイプに関連付けられた代替テキストのタイトルを返します。参照 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | チャートの軸へのアクセスを提供します。読み取り専用 [IAxesManager](../iaxesmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | 3D チャートの背面壁の書式を変更できるオブジェクトを返します。読み取り専用 [IChartWall](../ichartwall/)。 |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。参照 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | チャートに関連付けられたリンクまたは埋め込みデータに関する情報を返します。読み取り専用 [IChartData](../ichartdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | チャートのデータテーブルを返します。読み取り専用 [IDataTable](../idatatable/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | チャートのタイトルを返します。読み取り専用 [IChartTitle](../icharttitle/)。 |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | シェイプ上の接続ポイント数を返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../../aspose.slides/icustomdata/)。 |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | チャートで空白セルをプロットする方法を返します。参照 [DisplayBlanksAsType](../displayblanksastype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | [EffectFormat](../../aspose.slides/effectformat/) オブジェクト（シェイプに適用されたピクセルエフェクトを含む）を返します。注: エフェクトプロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | [FillFormat](../../aspose.slides/fillformat/) オブジェクト（シェイプの塗りつぶし書式プロパティを含む）を返します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | 3D チャートの床の書式を変更できるオブジェクトを返します。読み取り専用 [IChartWall](../ichartwall/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | シェイプフレームのプロパティを返します。参照 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | シェイプのロック状態を返します。読み取り専用 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | チャートにデータテーブルがあるかどうかを判定します。参照 **bool**。 |
| **bool** [get_HasLegend](./get_haslegend/)() override | チャートに凡例があるかどうかを判定します。参照 **bool**。 |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | チャート領域に角丸を適用するかどうかを指定します。参照 **bool**。 |
| **bool** [get_HasTitle](./get_hastitle/)() override | チャートに表示可能なタイトルがあるかどうかを判定します。参照 **bool**。 |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | シェイプの高さ（ポイント単位）を取得します。参照 **float**。 |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | シェイプが非表示かどうかを判定します。参照 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。参照 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。参照 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 装飾としてマークするオプションを取得/設定します。読み書き **bool**。 |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | チャートの凡例を返します。読み取り専用 [ILegend](../ilegend/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | [LineFormat](../../aspose.slides/lineformat/) オブジェクト（シェイプの線書式プロパティを含む）を返します。注: 線プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | シェイプの名前を返します。null であってはいけません。必要に応じて空文字列を使用してください。参照 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | スライド単位のユニーク識別子を返します。この識別子はシェイプの寿命中一定で、PowerPoint または interop コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 **uint32_t**。参照 [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | シェイプがグループ化されている場合は親 [GroupShape](../../aspose.slides/groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | シェイプのプレースホルダーを返します。プレースホルダーが無い場合は null を返します。読み取り専用 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | チャートのプロット領域を表します。読み取り専用 [IChartPlotArea](../ichartplotarea/)。 |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | 表示セルのみをプロットするかどうかを判定します。false の場合、表示セルと非表示セルの両方をプロットします。参照 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | スライドの親プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | シェイプフレームの生データプロパティを返します。参照 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | 指定されたシェイプが z 軸周りに回転している角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。参照 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | チャートの 3D 回転を返します。読み取り専用 [IRotation3D](../irotation3d/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | シェイプのロック状態を返します。読み取り専用 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | チャートの最大値上にデータラベルを表示するかどうかを指定します。参照 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | 3D チャートの側面壁の書式を変更できるオブジェクトを返します。読み取り専用 [IChartWall](../ichartwall/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | シェイプの親スライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | チャートスタイルを返します。参照 [StyleType](../styletype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | チャートのテキスト書式を返します。このプロパティは以下のタイプには適用できません: [ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/)。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | テーママネージャーを返します。読み取り専用 [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | [ThreeDFormat](../../aspose.slides/threedformat/) オブジェクト（シェイプの 3D エフェクトプロパティ）を返します。注: 3D プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | チャートタイプを返します。参照 [ChartType](../charttype/)。 |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | アドインやその他のコードが使用することを意図した、プレゼンテーション単位の内部識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的なユニークキーとして扱うべきではありません。読み取り専用 **uint32_t**。参照 [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | チャート上に描画されるシェイプを指定します。読み取り専用 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | シェイプの幅（ポイント単位）を取得します。参照 **float**。 |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | シェイプの左上隅の x 座標（ポイント単位）を取得します。参照 **float**。 |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | シェイプの左上隅の y 座標（ポイント単位）を取得します。参照 **float**。 |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | z オーダー内でのシェイプの位置を返します。Shapes[0] は最背面のシェイプを返し、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承しているレイアウトやマスタースライドからのシェイプ）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | シェイプのサムネイルを返します。[ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) シェイプサムネイル境界タイプがデフォルトで使用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | このシェイプがプレースホルダーではないことを定義します。 |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。書き込み [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | チャートで空白セルをプロットする方法を設定します。書き込み [DisplayBlanksAsType](../displayblanksastype/)。 |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | チャートにデータテーブルがあるかどうかを設定します。書き込み **bool**。 |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | チャートに凡例があるかどうかを設定します。書き込み **bool**。 |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | チャート領域に角丸を適用するかどうかを設定します。書き込み **bool**。 |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | チャートに表示可能なタイトルがあるかどうかを設定します。書き込み **bool**。 |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 装飾としてマークするオプションを設定します。読み書き **bool**。 |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | シェイプの名前を設定します。null であってはいけません。必要に応じて空文字列を使用してください。書き込み [System::String](../../system/string/)。 |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | 表示セルのみをプロットするかどうかを設定します。false の場合、表示セルと非表示セルの両方をプロットします。書き込み **bool**。 |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | シェイプフレームの生データプロパティを設定します。書き込み [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | 指定されたシェイプが z 軸周りに回転する角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | チャートの最大値上にデータラベルを表示するかどうかを設定します。書き込み **bool**。 |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | チャートスタイルを設定します。書き込み [StyleType](../styletype/)。 |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | チャートタイプを設定します。書き込み [ChartType](../charttype/)。 |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | シェイプの左上隅の x 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | シェイプの左上隅の y 座標（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタ（共有ではなく）に設定します。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| void [ValidateChartLayout](./validatechartlayout/)() override | チャート要素の実際の値を計算します。実際の値には、[IActualLayout](../iactuallayout/) インターフェースを実装する要素の位置（[IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)）および実際の軸値（[IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)）が含まれます。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [GraphicalObject](../../aspose.slides/graphicalobject/)
* クラス [IChart](../ichart/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)