---
title: ChartSeries
second_title: Aspose.Slides for C++ API リファレンス
description: チャートシリーズを表します。
type: docs
weight: 274
url: /ja/aspose.slides.charts/chartseries/
---
## ChartSeries クラス


Represents a chart series.

```cpp
class ChartSeries : public Aspose::Slides::Charts::IChartSeries,
                    public Aspose::Slides::IDOMObject
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみで使用されます。 |
| [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() override | 3-D 棒グラフのシリーズの形状を指定します。このプロパティの値を変更すると、シリーズの Type が自動的に変更される可能性があります。[ChartShapeType](../chartshapetype/) を参照してください。 |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | バブルチャートでバブルサイズ値がどのように表現されるかを指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() の**読み書き**プロパティで値を変更できます。 |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | バブルチャートのスケール係数を指定します（デフォルトサイズの 0〜300% の範囲）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() の**読み書き**プロパティで値を変更できます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 親チャートを返します。**読み取り専用** [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) override | 指定されたインデックスのこのシリーズのデータ ポイントを返します。 |
| **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() override | このシリーズのデータポイントのコレクションを返します。**読み取り専用** [IChartDataPointCollection](../ichartdatapointcollection/)。 |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | ドーナツチャートの穴のサイズを指定します（プロット領域サイズの 10〜90%）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() の**読み書き**プロパティで値を変更できます。**読み取り専用** **uint8_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() override | X 方向のシリーズの ErrorBars を表します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() override | Y 方向のシリーズの ErrorBars を表します。 |
| **int32_t** [get_Explosion](./get_explosion/)() override | 円グラフの開いたスライスの中心からの距離は、円の直径のパーセンテージで表されます。**読み取り** **int32_t**。 |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 最初の円またはドーナツチャートのスライスの角度を度単位で指定します（上から時計回りに 0〜360 度）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() の**読み書き**プロパティで値を変更できます。**読み取り専用** **uint16_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | シリーズのフォーマットを返します。**読み取り専用** [IFormat](../iformat/)。 |
| **int32_t** [get_GapDepth](./get_gapdepth/)() override | 3D チャートにおけるデータシリーズ間の距離を、マーカー幅のパーセンテージで指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() の**読み書き**プロパティで値を変更できます。**読み取り専用** **int32_t**。 |
| **int32_t** [get_GapWidth](./get_gapwidth/)() override | 棒または列クラスター間のスペースを、棒または列幅のパーセンテージで指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() の**読み書き**プロパティで値を変更できます。**読み取り専用** **int32_t**。 |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | このシリーズおよび関連するシリーズにシリーズラインがあるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() の**読み書き**プロパティで値を変更できます。ParentSeriesGroup.SeriesLinesFormat プロパティでシリーズラインの書式を設定します。**読み取り専用** **bool**。 |
| **bool** [get_HasUpDownBars](./get_hasupdownbars/)() override | Line- または Stock- チャートに上下バーがあるかどうかを決定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() の**読み書き**プロパティで値を変更できます。[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() プロパティで上下バーの書式を設定します。**読み取り専用** **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() override | シリーズの塗りつぶし色を反転させることを指定します。色設定を適用するには、シリーズのフォーマット FillType を [FillType::Solid](../../aspose.slides/filltype/) に設定してください。[ColorFormat](../../aspose.slides/colorformat/) を参照してください。 |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | 値が負の場合、棒、列、またはバブルシリーズの色を反転させることを指定します。**読み取り** **bool**。 |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | シリーズの各データマーカーが異なる色を持つことを指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() の**読み書き**プロパティで値を変更できます。**読み取り専用** **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) override | 指定されたインデックスのこのシリーズのデータポイントのデータラベルを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() override | シリーズのラベルを返します。**読み取り専用** [IDataLabelCollection](../idatalabelcollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | [Marker](../marker/)。**読み取り専用** [IMarker](../imarker/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() override | シリーズ名を返します。**読み取り専用** [IStringChartValue](../istringchartvalue/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() override | NumberFormatOfBubbleSizes。[System::String](../../system/string/) を**読み取り**。 |
| [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() override | NumberFormatOfValues。[System::String](../../system/string/) を**読み取り**。 |
| [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() override | NumberFormatOfXValues。[System::String](../../system/string/) を**読み取り**。 |
| [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() override | NumberFormatOfYValues。[System::String](../../system/string/) を**読み取り**。 |
| **int32_t** [get_Order](./get_order/)() override | シリーズの順序を返します。**int32_t** を**読み取り**。 |
| **int8_t** [get_Overlap](./get_overlap/)() override | 2-D チャートで棒や列がどれだけ重なるかをパーセンテージで指定します（-100% から 100%）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。値を変更するには [get_ParentSeriesGroup()->Overlap()](./get_parentseriesgroup/) の**読み書き**プロパティを使用してください。**読み取り専用** **int8_t**。 |
| [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() override | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) override | 指定されたインデックスの親シリーズグループ内のチャートシリーズを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() override | ParentSeriesGroup。**読み取り専用** [IChartSeriesGroup](../ichartseriesgroup/)。 |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第 2 のパイまたはバーに含まれるかを決定する方法を指定します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() の**読み書き**プロパティで値を変更できます。**読み取り専用** [PieSplitType](../piesplittype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | pie-of-pie または bar-of-pie チャートのカスタム分割情報を返します。指定されたインデックスの第 2 のパイまたはバーに描画されるデータポイントを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | pie-of-pie または bar-of-pie チャートのカスタム分割情報のコレクションを返します。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。**読み取り専用** [PieSplitCustomPointCollection](../piesplitcustompointcollection/)。 |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | pie-of-pie または bar-of-pie チャートで、どのデータポイントが第 2 のパイまたはバーに含まれるかを決定するために使用される値を指定します。PieSplitBy プロパティと併せて使用されます。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() の**読み書き**プロパティで値を変更できます。**読み取り専用** **double**。 |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | このシリーズが二次軸にプロットされているかどうかを示します。**bool** を**読み取り**。 |
| [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() override | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | このシリーズに関連する凡例エントリを表します。**読み取り専用** [ILegendEntryProperties](../ilegendentryproperties/)。 |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | pie-of-pie または bar-of-pie チャートの第 2 のパイまたはバーのサイズを、最初のパイのサイズのパーセンテージで指定します（5〜200%）。このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに投影されたプロパティです。そのため、**読み取り専用**です。ParentSeriesGroup プロパティでアクセスし、[get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() の**読み書き**プロパティで値を変更できます。**読み取り専用** **uint16_t**。 |
| **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() override | コネクタラインを表します。Waterfall チャートにのみ適用されます。 |
| **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() override | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** を**読み取り**。 |
| **bool** [get_ShowMeanLine](./get_showmeanline/)() override | 平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** を**読み取り**。 |
| **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() override | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** を**読み取り**。 |
| **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() override | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** を**読み取り**。 |
| **bool** [get_Smooth](./get_smooth/)() override | 曲線スムージングを表します。ラインチャートまたは散布図で曲線スムージングが有効な場合は **true** です。ラインと線で接続された散布図チャートにのみ適用されます。**bool** を**読み取り**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) override | 指定されたインデックスのトレンドラインを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() override | シリーズのトレンドラインのコレクション。**読み取り専用** [ITrendlineCollection](../itrendlinecollection/)。 |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | このシリーズのタイプを返します。[ChartType](../charttype/) を**読み取り**。 |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() override | シリーズインデックスとチャートスタイルに基づく自動カラーを返します。FillType が NotDefined の場合はデフォルトでこの色が使用されます。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) override | 3-D 棒グラフのシリーズの形状を指定します。このプロパティの値を変更すると、シリーズの Type が自動的に変更される可能性があります。[ChartShapeType](../chartshapetype/) に書き込みます。 |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | 円グラフの開いたスライスの中心からの距離は、円の直径のパーセンテージで表されます。**int32_t** に書き込みます。 |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | 値が負の場合、棒、列、またはバブルシリーズの色を反転させることを指定します。**bool** に書き込みます。 |
| void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) override | NumberFormatOfBubbleSizes。[System::String](../../system/string/) に書き込みます。 |
| void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) override | NumberFormatOfValues。[System::String](../../system/string/) に書き込みます。 |
| void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) override | NumberFormatOfXValues。[System::String](../../system/string/) に書き込みます。 |
| void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) override | NumberFormatOfYValues。[System::String](../../system/string/) に書き込みます。 |
| void [set_Order](./set_order/)(**int32_t**) override | シリーズの順序を返します。**int32_t** に書き込みます。 |
| void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) override | 親カテゴリラベルのレイアウトを表します。Treemap チャートにのみ適用されます。 |
| void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) override | このシリーズが二次軸にプロットされているかどうかを示します。**bool** に書き込みます。 |
| void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) override | 四分位法を表します。BoxAndWhisker チャートにのみ適用されます。 |
| void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) override | コネクタラインを表します。Waterfall チャートにのみ適用されます。 |
| void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) override | 内部ポイントを表します。BoxAndWhisker チャートで内部ポイントが表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** に書き込みます。 |
| void [set_ShowMeanLine](./set_showmeanline/)(**bool**) override | 平均線を表します。BoxAndWhisker チャートで平均線が表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** に書き込みます。 |
| void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) override | 平均マーカーを表します。BoxAndWhisker チャートで平均マーカーが表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** に書き込みます。 |
| void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) override | 外れ値ポイントを表します。BoxAndWhisker チャートで外れ値ポイントが表示されている場合は **true** です。BoxAndWhisker チャートにのみ適用されます。**bool** に書き込みます。 |
| void [set_Smooth](./set_smooth/)(**bool**) override | 曲線スムージングを表します。ラインチャートまたは散布図で曲線スムージングが有効な場合は **true** です。ラインと線で接続された散布図チャートにのみ適用されます。**bool** に書き込みます。 |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | このシリーズのタイプを返します。[ChartType](../charttype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IChartSeries](../ichartseries/)
* クラス [IDOMObject](../../aspose.slides/idomobject/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)