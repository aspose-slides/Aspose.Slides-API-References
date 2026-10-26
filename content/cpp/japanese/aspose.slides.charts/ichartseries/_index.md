---
title: IChartSeries
second_title: Aspose.Slides for C++ API リファレンス
description: チャートシリーズを表します。
type: docs
weight: 820
url: /ja/aspose.slides.charts/ichartseries/
---
## IChartSeries クラス


チャートシリーズを表します。

```cpp
class IChartSeries : public Aspose::Slides::Charts::IChartComponent
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| virtual [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() | 3-D 棒グラフのシリーズの形状を指定します。このプロパティの値を変更すると、シリーズの Type が自動的に変更される可能性があります。[ChartShapeType](../chartshapetype/) を参照してください。 |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | バブルチャートでバブルサイズの値がどのように表現されるかを指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() の読み書きプロパティを使用して値を変更します。 |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300％ の範囲）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() の読み書きプロパティで値を変更します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | チャートを返します。読み取り専用 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) | 指定されたインデックスのこのシリーズのデータポイントを返します。 |
| virtual **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() | このシリーズのデータポイントのコレクションを返します。読み取り専用 [IChartDataPointCollection](../ichartdatapointcollection/)。 |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | ドーナツチャートの穴のサイズを指定します（プロット領域サイズの 10％〜90％ の範囲）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() の読み書きプロパティを使用して値を変更します。読み取り専用 **uint8_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() | X 方向の ErrorBars を表します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() | Y 方向の ErrorBars を表します。 |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | 円グラフの開いたスライスと中心の距離は、円径のパーセンテージで表されます。読み取り **int32_t**。 |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 最初の円またはドーナツチャートのスライスの角度を度で指定します（上から時計回り、0〜360 度）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用して親シリーズグループにアクセスします。[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() の読み書きプロパティを使用して値を変更します。読み取り専用 **uint16_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | シリーズの書式を返します。読み取り専用 [IFormat](../iformat/)。 |
| virtual **int32_t** [get_GapDepth](./get_gapdepth/)() | 3D チャートのデータシリーズ間の距離をマーカー幅のパーセンテージで返します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() の読み書きプロパティで値を変更します。読み取り専用 **int32_t**。 |
| virtual **int32_t** [get_GapWidth](./get_gapwidth/)() | 棒や柱のクラスター間の間隔を棒や柱の幅のパーセンテージで指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() の読み書きプロパティで値を変更します。読み取り専用 **int32_t**。 |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | このシリーズおよび関連シリーズにシリーズラインがあるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用し、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() の読み書きプロパティで値を変更します。ParentSeriesGroup.SeriesLinesFormat プロパティを使用してシリーズラインの書式を設定します。読み取り専用 **bool**。 |
| virtual **bool** [get_HasUpDownBars](./get_hasupdownbars/)() | ラインまたはストックチャートに上下バーがあるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用し、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() の読み書きプロパティで値を変更します。[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() プロパティを使用して上下バーの書式を設定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() | シリーズのインバートされた実体色を指定します。色設定を適用するには、シリーズ書式の FillType を [FillType::Solid](../../aspose.slides/filltype/) に設定します。[IColorFormat](../../aspose.slides/icolorformat/) を参照してください。 |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | 値が負の場合、棒、柱、またはバブルシリーズの色を反転させるかどうかを指定します。読み取り **bool**。 |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | 各データマーカーが異なる色になるかどうかを指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用し、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() の読み書きプロパティで値を変更します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) | 指定されたインデックスのこのシリーズのデータポイントのラベルを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() | シリーズのラベルを返します。読み取り専用 [IDataLabelCollection](../idatalabelcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | シリーズマーカーを返します。読み取り専用 [IMarker](../imarker/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() | シリーズ名を返します。読み取り専用 [IStringChartValue](../istringchartvalue/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() | シリーズのバブルサイズの数値書式を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() | シリーズの数値書式を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() | シリーズの X 値の数値書式を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() | シリーズの Y 値の数値書式を返します。読み取り [System::String](../../system/string/)。 |
| virtual **int32_t** [get_Order](./get_order/)() | シリーズの順序を返します。読み取り **int32_t**。 |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 2-D チャートで棒と柱が重なる割合をパーセンテージで指定します（-100％〜100％ の範囲）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。値を変更するには [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_Overlap() の読み書きプロパティを使用します。読み取り専用 **int8_t**。 |
| virtual [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](./)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) | 指定されたインデックスの親シリーズグループ内のチャートシリーズを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() | 親シリーズグループを返します。読み取り専用 [IChartSeriesGroup](../ichartseriesgroup/)。 |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Pie-of-pie または Bar-of-pie チャートで、どのデータポイントが第 2 の円または棒に属するかを決定する方法を指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用し、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() の読み書きプロパティで値を変更します。読み取り専用 [PieSplitType](../piesplittype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | カスタム分割情報を持つ Pie-of-pie または Bar-of-pie チャートで、指定されたインデックスの第 2 の円または棒に描画されるデータポイントを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | カスタム分割情報を持つ Pie-of-pie または Bar-of-pie チャートで、第 2 の円または棒に描画されるデータポイントの集合を保持します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)。 |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Pie-of-pie または Bar-of-pie チャートで第 2 の円または棒に属するデータポイントを決定するために使用される値を指定します。PieSplitBy プロパティと組み合わせて使用します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用し、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() の読み書きプロパティで値を変更します。読み取り専用 **double**。 |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | このシリーズが第 2 の値軸にプロットされているかどうかを示します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | このシリーズに関連する凡例エントリを表します。読み取り専用 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Pie-of-pie または Bar-of-pie チャートの第 2 の円または棒のサイズを、最初の円のサイズのパーセンテージで指定します（5〜200％ の範囲）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影され、読み取り専用です。ParentSeriesGroup プロパティを使用し、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() の読み書きプロパティで値を変更します。読み取り専用 **uint16_t**。 |
| virtual **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() | コネクタラインを表します。Waterfall チャートにのみ適用されます。 |
| virtual **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り **bool**。 |
| virtual **bool** [get_ShowMeanLine](./get_showmeanline/)() | 平均マーカーを表します。BoxAndWhisker チャートで平均ラインが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り **bool**。 |
| virtual **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り **bool**。 |
| virtual **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 基本スライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual **bool** [get_Smooth](./get_smooth/)() | カーブ平滑化を表します。ラインチャートまたは散布図チャートでカーブ平滑化が有効になっている場合は true です。ラインと散布図（線で接続される）チャートにのみ適用されます。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) | 指定されたインデックスのトレンドラインを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() | シリーズトレンドラインのコレクションを返します。読み取り専用 [ITrendlineCollection](../itrendlinecollection/)。 |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | このシリーズのタイプを返します。読み取り [ChartType](../charttype/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() | シリーズインデックスとチャートスタイルに基づく自動カラーを返します。FillType が NotDefined の場合、既定でこの色が使用されます。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローンを可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) | 3-D 棒グラフのシリーズの形状を指定します。このプロパティの値を変更すると、シリーズの Type が自動的に変更される可能性があります。[ChartShapeType](../chartshapetype/) に書き込みます。 |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | 円グラフの開いたスライスと中心の距離は、円径のパーセンテージで表されます。{{int32_t}} に書き込みます。 |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | 値が負の場合、棒、柱、またはバブルシリーズの色を反転させるかどうかを指定します。{{bool}} に書き込みます。 |
| virtual void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) | シリーズバブルサイズの数値書式を設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) | シリーズ値の数値書式を設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) | シリーズ X 値の数値書式を設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) | シリーズ Y 値の数値書式を設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_Order](./set_order/)(**int32_t**) | シリーズの順序を書き込みます。{{int32_t}} に書き込みます。 |
| virtual void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| virtual void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) | このシリーズが第 2 の値軸にプロットされているかどうかを書き込みます。{{bool}} に書き込みます。 |
| virtual void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| virtual void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) | コネクタラインを表します。Waterfall チャートにのみ適用されます。 |
| virtual void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。{{bool}} に書き込みます。 |
| virtual void [set_ShowMeanLine](./set_showmeanline/)(**bool**) | 平均マーカーを表します。BoxAndWhisker チャートで平均ラインが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。{{bool}} に書き込みます。 |
| virtual void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。{{bool}} に書き込みます。 |
| virtual void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は true です。BoxAndWhisker チャートにのみ適用されます。{{bool}} に書き込みます。 |
| virtual void [set_Smooth](./set_smooth/)(**bool**) | カーブ平滑化を表します。ラインまたは散布図（線で接続）チャートでカーブ平滑化が有効になっている場合は true です。ラインと散布図（線で接続）チャートにのみ適用されます。{{bool}} に書き込みます。 |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | このシリーズのタイプを返します。[ChartType](../charttype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照（shared ではなく）に設定します。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、戻します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* Class [IChartComponent](../ichartcomponent/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)