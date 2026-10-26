---
title: IChartSeries
second_title: Aspose.Slides for C++ API 參考
description: 代表一個圖表系列。
type: docs
weight: 820
url: /zh-hant/aspose.slides.charts/ichartseries/
---
## IChartSeries 類別

表示圖表系列。

```cpp
class IChartSeries : public Aspose::Slides::Charts::IChartComponent
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() | 指定 3-D 柱狀圖系列的形狀。變更此屬性的值可能會自動變更系列的 Type。讀取 [ChartShapeType](../chartshapetype/)。 |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | 指定氣泡圖上氣泡大小值的呈現方式。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() 讀寫屬性以變更值。 |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | 指定氣泡圖的比例因子（可在預設大小的 0% 到 300% 之間）。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() 讀寫屬性以變更值。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 返回圖表。唯讀 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) | 返回此系列在指定索引處的資料點。 |
| virtual **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() | 返回此系列的資料點集合。唯讀 [IChartDataPointCollection](../ichartdatapointcollection/)。 |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | 指定甜甜圈圖中孔洞的大小（可在圖表區域大小的 10% 到 90% 之間）。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() 讀寫屬性以變更值。唯讀 **uint8_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() | 表示方向 X 的系列 ErrorBars。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() | 表示方向 Y 的系列 ErrorBars。 |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | 開啟的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。讀取 **int32_t**。 |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | 指定第一個餅圖或甜甜圈圖切片的角度（度，順時針方向，0 到 360 度）。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() 讀寫屬性以變更值。唯讀 **uint16_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 返回系列的格式。唯讀 [IFormat](../iformat/)。 |
| virtual **int32_t** [get_GapDepth](./get_gapdepth/)() | 返回 3D 圖表中資料系列之間，以標記寬度百分比表示的距離。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() 讀寫屬性以變更值。唯讀 **int32_t**。 |
| virtual **int32_t** [get_GapWidth](./get_gapwidth/)() | 指定條形或柱形叢集之間的間距，以條形或柱形寬度的百分比表示。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() 讀寫屬性以變更值。唯讀 **int32_t**。 |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | 判斷此系列及相關系列是否有系列線。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() 讀寫屬性以變更值。使用 ParentSeriesGroup.SeriesLinesFormat 屬性以設定系列線格式。唯讀 **bool**。 |
| virtual **bool** [get_HasUpDownBars](./get_hasupdownbars/)() | 判斷折線圖或股票圖是否具有上/下棒。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() 讀寫屬性以變更值。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() 屬性以設定上/下棒格式。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() | 指定系列的倒轉實色。要套用顏色設定，將系列格式的 FillType 設為 [FillType::Solid](../../aspose.slides/filltype/)。讀取 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | 指定若值為負，則條形、柱形或氣泡系列應倒轉其顏色。讀取 **bool**。 |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | 指定系列中的每個資料標記具有不同的顏色。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() 讀寫屬性以變更值。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) | 返回此系列在指定索引處的資料點的資料標籤。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() | 返回系列的 Labels。唯讀 [IDataLabelCollection](../idatalabelcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | 返回系列的標記。唯讀 [IMarker](../imarker/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() | 返回系列名稱。唯讀 [IStringChartValue](../istringchartvalue/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() | 返回系列氣泡大小的數字格式。讀取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() | 返回系列值的數字格式。讀取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() | 返回系列 X 值的數字格式。讀取 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() | 返回系列 Y 值的數字格式。讀取 [System::String](../../system/string/)。 |
| virtual **int32_t** [get_Order](./get_order/)() | 返回系列的順序。讀取 **int32_t**。 |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 指定 2D 圖表上條形和柱形的重疊程度，以百分比表示（-100% 到 100%）。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。要變更值，請使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_Overlap() 讀寫屬性。唯讀 **int8_t**。 |
| virtual [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() | 表示父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](./)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) | 返回父系列組中在指定索引處的圖表系列。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() | 返回父系列組。唯讀 [IChartSeriesGroup](../ichartseriesgroup/)。 |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | 指定如何決定 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個餅或條。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() 讀寫屬性以變更值。唯讀 [PieSplitType](../piesplittype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | 自訂分割資訊，用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。返回在指定索引處應在第二個餅或條中繪製的資料點。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | 自訂分割資訊，用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。包含應在第二個餅或條中繪製的資料點。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。唯讀 [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)。 |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | 指定用於決定 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個餅或條的值。與 PieSplitBy 屬性一起使用。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() 讀寫屬性以變更值。唯讀 **double**。 |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | 指示此系列是否繪製在第二個值軸上。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 返回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() | 表示四分位方法。僅適用於 BoxAndWhisker 圖表。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 表示與此系列相關的圖例項目。唯讀 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | 指定 pie-of-pie 或 bar-of-pie 圖表中第二個餅或條的大小，以第一個餅的大小百分比表示（可在 5% 到 200% 之間）。此屬性不僅屬於此系列，也屬於所有父系列組的系列——此為相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() 讀寫屬性以變更值。唯讀 **uint16_t**。 |
| virtual **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() | 表示連接線。僅適用於 Waterfall 圖表。 |
| virtual **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() | 表示內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| virtual **bool** [get_ShowMeanLine](./get_showmeanline/)() | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均線則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| virtual **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| virtual **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() | 表示離群點。若在 BoxAndWhisker 圖表上顯示離群點則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 返回基礎投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual **bool** [get_Smooth](./get_smooth/)() | 表示曲線平滑。若對折線圖或散點圖啟用曲線平滑則為 true。僅適用於折線圖與連線散點圖。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) | 返回指定索引處的趨勢線。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() | 系列趨勢線的集合。唯讀 [ITrendlineCollection](../itrendlinecollection/)。 |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | 返回此系列的類型。讀取 [ChartType](../charttype/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() | 返回根據系列索引和圖表樣式自動決定的系列顏色。如果 FillType 等於 NotDefined，則預設使用此顏色。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參照計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參照計數器減少指定的值。 |
| virtual void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) | 指定 3-D 柱狀圖系列的形狀。變更此屬性的值可能會自動變更系列的 Type。寫入 [ChartShapeType](../chartshapetype/)。 |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | 開啟的餅圖切片與中心的距離以餅圖直徑百分比表示。寫入 **int32_t**。 |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | 指定條形、柱形或氣泡系列在值為負時應倒轉其顏色。寫入 **bool**。 |
| virtual void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) | 設定系列氣泡大小的數字格式。寫入 [System::String](../../system/string/)。 |
| virtual void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) | 設定系列值的數字格式。寫入 [System::String](../../system/string/)。 |
| virtual void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) | 設定系列 X 值的數字格式。寫入 [System::String](../../system/string/)。 |
| virtual void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) | 設定系列 Y 值的數字格式。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Order](./set_order/)(**int32_t**) | 返回系列的順序。寫入 **int32_t**。 |
| virtual void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) | 表示父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| virtual void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) | 指示此系列是否繪製在第二個值軸上。寫入 **bool**。 |
| virtual void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) | 表示四分位方法。僅適用於 BoxAndWhisker 圖表。 |
| virtual void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) | 表示連接線。僅適用於 Waterfall 圖表。 |
| virtual void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) | 表示內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| virtual void [set_ShowMeanLine](./set_showmeanline/)(**bool**) | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均線則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| virtual void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| virtual void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) | 表示離群點。若在 BoxAndWhisker 圖表上顯示離群點則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| virtual void [set_Smooth](./set_smooth/)(**bool**) | 表示曲線平滑。若對折線圖或散點圖啟用曲線平滑則為 true。僅適用於折線圖與連線散點圖。寫入 **bool**。 |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | 返回此系列的類型。寫入 [ChartType](../charttype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [IChartComponent](../ichartcomponent/)
* 名稱空間 [Aspose::Slides::Charts](../)
* 程式庫 [Aspose.Slides](../../)