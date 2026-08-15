---
title: ChartSeries
second_title: Aspose.Slides for C++ API Reference
description: 表示圖表系列。
type: docs
weight: 274
url: /zh-hant/aspose.slides.charts/chartseries/
---
## ChartSeries 類別

表示圖表系列。

```cpp
class ChartSeries : public Aspose::Slides::Charts::IChartSeries,
                    public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 比較物件，使用 C# [Object.Equals](../../system/object/equals/) 語意。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 比較參考型別物件，使用 C# 風格。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 比較值型別物件，使用 C# 風格。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() override | 指定 3D 長條圖系列的形狀。變更此屬性的值可能會自動變更系列的類型。讀取 [ChartShapeType](../chartshapetype/)。 |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | 指定泡泡圖上泡泡大小值的表示方式。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() 讀寫屬性來變更值。 |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | 指定泡泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() 讀寫屬性來變更值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 傳回父圖表。唯讀 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) override | 傳回此系列在指定索引處的資料點。 |
| **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() override | 傳回此系列的資料點集合。唯讀 [IChartDataPointCollection](../ichartdatapointcollection/)。 |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | 指定甜甜圈圖中孔洞的大小（可介於繪圖區大小的 10% 到 90% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() 讀寫屬性來變更值。唯讀 **uint8_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() override | 表示 X 方向的系列誤差棒。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() override | 表示 Y 方向的系列誤差棒。 |
| **int32_t** [get_Explosion](./get_explosion/)() override | 打開的圓餅切片與圓餅圖中心的距離，以圓餅直徑的百分比表示。讀取 **int32_t**。 |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | 指定第一個圓餅或甜甜圈圖切片的角度（以度為單位，從上方順時鐘方向，0 到 360 度）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() 讀寫屬性來變更值。唯讀 **uint16_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 傳回系列的格式。唯讀 [IFormat](../iformat/)。 |
| **int32_t** [get_GapDepth](./get_gapdepth/)() override | 以標記寬度的百分比表示，在 3D 圖表中資料系列之間的距離。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() 讀寫屬性來變更值。唯讀 **int32_t**。 |
| **int32_t** [get_GapWidth](./get_gapwidth/)() override | 指定條形或柱形叢集之間的間距，以條形或柱形寬度的百分比表示。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() 讀寫屬性來變更值。唯讀 **int32_t**。 |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | 判斷此系列及相關系列是否具有系列線。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() 讀寫屬性來變更值。使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線的格式。唯讀 **bool**。 |
| **bool** [get_HasUpDownBars](./get_hasupdownbars/)() override | 判斷折線圖或股票圖是否有上下條。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() 讀寫屬性來變更值。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() 屬性設定上下條的格式。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() override | 指定系列的反向實色。若要套用顏色設定，將系列格式的 FillType 設為 [FillType::Solid](../../aspose.slides/filltype/)。讀取 [ColorFormat](../../aspose.slides/colorformat/)。 |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | 指定當值為負時，長條、柱形或泡泡系列應反轉其顏色。讀取 **bool**。 |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | 指定系列中的每個資料標記具有不同的顏色。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() 讀寫屬性來變更值。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) override | 傳回此系列在指定索引處的資料點標籤。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() override | 傳回系列的 Labels。唯讀 [IDataLabelCollection](../idatalabelcollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | [Marker](../marker/). 唯讀 [IMarker](../imarker/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() override | 傳回系列名稱。唯讀 [IStringChartValue](../istringchartvalue/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() override | NumberFormatOfBubbleSizes. 讀取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() override | NumberFormatOfValues. 讀取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() override | NumberFormatOfXValues. 讀取 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() override | NumberFormatOfYValues. 讀取 [System::String](../../system/string/)。 |
| **int32_t** [get_Order](./get_order/)() override | 傳回系列的順序。讀取 **int32_t**。 |
| **int8_t** [get_Overlap](./get_overlap/)() override | 指定 2D 圖表中長條與柱形的重疊程度，以百分比表示（從 -100% 到 100%）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。若要變更值，請使用 [get_ParentSeriesGroup()->Overlap()](./get_parentseriesgroup/) 讀寫屬性。唯讀 **int8_t**。 |
| [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() override | 表示父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) override | 傳回父系列群組中指定索引處的圖表系列。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() override | ParentSeriesGroup。唯讀 [IChartSeriesGroup](../ichartseriesgroup/)。 |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | 指定如何決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個圓餅或條形。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() 讀寫屬性來變更值。唯讀 [PieSplitType](../piesplittype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | 自訂分割資訊，用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。傳回應在指定索引處於第二個圓餅或條形中繪製的資料點。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | 自訂分割資訊，用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。包含應在第二個圓餅或條形中繪製的資料點。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。唯讀 [PieSplitCustomPointCollection](../piesplitcustompointcollection/)。 |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | 指定一個值，用於決定在 pie-of-pie 或 bar-of-pie 圖表中哪些資料點位於第二個圓餅或條形。與 PieSplitBy 屬性一起使用。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() 讀寫屬性來變更值。唯讀 **double**。 |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | 表示此系列是否繪製於次要軸。讀取 **bool**。 |
| [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() override | 表示四分位數方法。僅適用於 BoxAndWhisker 圖表。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | 表示與此系列相關的圖例項目。唯讀 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | 指定 pie-of-pie 或 bar-of-pie 圖表第二個圓餅或條形的大小，以第一個圓餅的大小百分比表示（可介於 5% 到 200% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——是對應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() 讀寫屬性來變更值。唯讀 **uint16_t**。 |
| **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() override | 表示連接線。僅適用於 Waterfall 圖表。 |
| **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() override | 表示內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| **bool** [get_ShowMeanLine](./get_showmeanline/)() override | 表示平均線。若在 BoxAndWhisker 圖表上顯示平均線則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() override | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() override | 表示異常值點。若在 BoxAndWhisker 圖表上顯示異常值點則為 true。僅適用於 BoxAndWhisker 圖表。讀取 **bool**。 |
| **bool** [get_Smooth](./get_smooth/)() override | 表示曲線平滑。若折線圖或散點圖的曲線平滑功能已開啟則為 true。僅適用於折線圖及連線散點圖。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) override | 傳回指定索引處的趨勢線。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() override | 系列趨勢線的集合。唯讀 [ITrendlineCollection](../itrendlinecollection/)。 |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | 傳回此系列的類型。讀取 [ChartType](../charttype/)。 |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() override | 根據系列索引與圖表樣式傳回系列的自動顏色。如 FillType 等於 NotDefined，則預設使用此顏色。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的類型實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的克隆。 |
|   [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化版。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) override | 指定 3D 長條圖系列的形狀。變更此屬性的值可能會自動變更系列的類型。寫入 [ChartShapeType](../chartshapetype/)。 |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | 打開的圓餅切片與圓餅圖中心的距離，以圓餅直徑的百分比表示。寫入 **int32_t**。 |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | 指定當值為負時，長條、柱形或泡泡系列應反轉其顏色。寫入 **bool**。 |
| void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) override | NumberFormatOfBubbleSizes。寫入 [System::String](../../system/string/)。 |
| void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) override | NumberFormatOfValues。寫入 [System::String](../../system/string/)。 |
| void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) override | NumberFormatOfXValues。寫入 [System::String](../../system/string/)。 |
| void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) override | NumberFormatOfYValues。寫入 [System::String](../../system/string/)。 |
| void [set_Order](./set_order/)(**int32_t**) override | 傳回系列的順序。寫入 **int32_t**。 |
| void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) override | 表示父類別標籤的版面配置。僅適用於 Treemap 圖表。 |
| void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) override | 表示此系列是否繪製於次要軸。寫入 **bool**。 |
| void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) override | 表示四分位數方法。僅適用於 BoxAndWhisker 圖表。 |
| void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) override | 表示連接線。僅適用於 Waterfall 圖表。 |
| void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) override | 表示內部點。若在 BoxAndWhisker 圖表上顯示內部點則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| void [set_ShowMeanLine](./set_showmeanline/)(**bool**) override | 表示平均線。若在 BoxAndWhisker 圖表上顯示平均線則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) override | 表示平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) override | 表示異常值點。若在 BoxAndWhisker 圖表上顯示異常值點則為 true。僅適用於 BoxAndWhisker 圖表。寫入 **bool**。 |
| void [set_Smooth](./set_smooth/)(**bool**) override | 表示曲線平滑。若折線圖或散點圖的曲線平滑功能已開啟則為 true。僅適用於折線圖及連線散點圖。寫入 **bool**。 |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | 傳回此系列的類型。寫入 [ChartType](../charttype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [IChartSeries](../ichartseries/)
* 類別 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空間 [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)