---
title: IChart
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のグラフィックチャートを表します。
type: docs
weight: 573
url: /ja/aspose.slides.charts/ichart/
---
## IChart クラス


スライド上のグラフィックチャートを表します。

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | このテーマ適用可能オブジェクトの有効なテーマを返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | シェイプに関連付けられた代替テキストを返します。参照 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | シェイプに関連付けられた代替テキストのタイトルを返します。参照 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | チャート軸へのアクセスを提供します。読み取り専用 [IAxesManager](../iaxesmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | 3D チャートの背面壁の書式を変更できるオブジェクトを返します。読み取り専用 [IChartWall](../ichartwall/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。参照 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](./)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | チャートに関連付けられたリンクまたは埋め込みデータに関する情報を返します。読み取り専用 [IChartData](../ichartdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | チャートのデータテーブルを返します。読み取り専用 [IDataTable](../idatatable/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | チャートタイトルを返します。読み取り専用 [IChartTitle](../icharttitle/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | シェイプ上の接続ポイント数を返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../../aspose.slides/icustomdata/)。 |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | チャートで空白セルをプロットする方法を返します。参照 [DisplayBlanksAsType](../displayblanksastype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | シェイプに適用されたピクセル効果を含む [EffectFormat](../../aspose.slides/effectformat/) オブジェクトを返します。読み取り専用 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | シェイプの塗りつぶし書式プロパティを含む [FillFormat](../../aspose.slides/fillformat/) オブジェクトを返します。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | 3D チャートの床の書式を変更できるオブジェクトを返します。読み取り専用 [IChartWall](../ichartwall/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | シェイプフレームのプロパティを返します。参照 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | シェイプのロックを返します。読み取り専用 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | チャートにデータテーブルがあるかどうかを判定します。取得 **bool**。 |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | チャートに凡例があるかどうかを判定します。取得 **bool**。 |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | チャート領域が角丸であるかを指定します。取得 **bool**。 |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | チャートに表示可能なタイトルがあるかどうかを判定します。取得 **bool**。 |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | シェイプの高さ（ポイント単位）を取得します。取得 **float**。 |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | シェイプが非表示かどうかを判定します。取得 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。参照 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャー。読み取り専用 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。参照 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | 「装飾としてマーク」オプションを取得します。取得/設定 **bool**。 |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | シェイプが TextHolder かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | チャートの凡例を返します。読み取り専用 [ILegend](../ilegend/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | シェイプの線書式プロパティを含む [LineFormat](../../aspose.slides/lineformat/) オブジェクトを返します。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | シェイプの名前を返します。参照 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | シェイプの存続期間中に一定で、PowerPoint またはインターロップコードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの固有識別子を返します。読み取り専用 **uint32_t**。詳細は [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | シェイプがグループ化されている場合、親 [GroupShape](../../aspose.slides/groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | チャートのプロット領域を表します。読み取り専用 [IChartPlotArea](../ichartplotarea/)。 |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | 表示されているセルのみをプロットするかどうかを判定します。false の場合、表示セルと非表示セルの両方をプロットします。取得 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 生のシェイプフレームのプロパティを返します。参照 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 指定されたシェイプが z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。取得 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | チャートの 3D 回転を返します。読み取り専用 [IRotation3D](../irotation3d/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | チャートの最大値を超えるデータラベルを表示するかを指定します。取得 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | 3D チャートの側壁の書式を変更できるオブジェクトを返します。読み取り専用 [IChartWall](../ichartwall/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | チャートスタイルを返します。参照 [StyleType](../styletype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | チャートのテキスト書式を返します。読み取り専用 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | オーバーライドテーママネージャーを返します。読み取り専用 [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | シェイプの線書式プロパティを含む [ThreeDFormat](../../aspose.slides/threedformat/) オブジェクトを返します。読み取り専用 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | チャートタイプを返します。参照 [ChartType](../charttype/)。 |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | アドインやその他のコードが使用することを意図した、プレゼンテーションスコープの内部識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能であるため、永続的なユニークキーとして扱うべきではありません。読み取り専用 **uint32_t**。詳細は [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | チャートの上に描画されるシェイプを指定します。読み取り専用 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | シェイプの幅（ポイント単位）を取得します。取得 **float**。 |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | シェイプの左上隅の x 座標（ポイント単位）を取得します。取得 **float**。 |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | シェイプの左上隅の y 座標（ポイント単位）を取得します。取得 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | z オーダーにおけるシェイプの位置を返します。Shapes[0] は z オーダーの最背面のシェイプを、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承するレイアウトおよび/またはマスタースライド上のシェイプ）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | シェイプのサムネイルを返します。[ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) シェイプサムネイル境界タイプがデフォルトで使用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | このシェイプがプレースホルダーではないことを定義します。 |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストを設定します。設定 [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストのタイトルを設定します。設定 [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。設定 [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | チャートで空白セルをプロットする方法を設定します。設定 [DisplayBlanksAsType](../displayblanksastype/)。 |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | シェイプフレームのプロパティを設定します。設定 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | チャートにデータテーブルがあるかどうかを判定します。設定 **bool**。 |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | チャートに凡例があるかどうかを判定します。設定 **bool**。 |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | チャート領域が角丸になるかを指定します。設定 **bool**。 |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | チャートに表示可能なタイトルがあるかどうかを判定します。設定 **bool**。 |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | シェイプの高さ（ポイント単位）を設定します。設定 **float**。 |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | シェイプが非表示かどうかを判定します。設定 **bool**。 |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。設定 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。設定 [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | 「装飾としてマーク」オプションを設定します。取得/設定 **bool**。 |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | シェイプの名前を設定します。設定 [System::String](../../system/string/)。 |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | 表示セルのみをプロットするかどうかを判定します。設定 **bool**。 |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 生のシェイプフレームのプロパティを設定します。設定 [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 指定されたシェイプが z 軸周りに回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。設定 **float**。 |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | チャートの最大値を超えるデータラベルを表示するかを指定します。設定 **bool**。 |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | チャートスタイルを設定します。設定 [StyleType](../styletype/)。 |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | チャートタイプを設定します。設定 [ChartType](../charttype/)。 |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | シェイプの幅（ポイント単位）を設定します。設定 **float**。 |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | シェイプの左上隅の x 座標（ポイント単位）を設定します。設定 **float**。 |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | シェイプの左上隅の y 座標（ポイント単位）を設定します。設定 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | チャート要素の実際の値を計算します。実際の値には、[IActualLayout](../iactuallayout/) インターフェイスを実装する要素（[IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)）の位置と、実際の軸値（[IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)）が含まれます。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* クラス [IFormattedTextContainer](../iformattedtextcontainer/)
* クラス [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)