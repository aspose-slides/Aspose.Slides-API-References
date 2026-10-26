---
title: IAxis
second_title: Aspose.Slides for C++ API 參考
description: 封裝了表示圖表坐標軸的物件。
type: docs
weight: 534
url: /zh-hant/aspose.slides.charts/iaxis/
---
## IAxis 類別


封裝了表示圖表坐標軸的物件。

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | 指定軸的實際主要單位。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | 指定軸的實際主要單位比例。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | 指定軸上的實際最大值。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | 指定軸的實際次要單位。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | 指定軸的實際次要單位比例。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | 指定軸上的實際最小值。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | 表示類別軸的彙總類型（分箱）。套用於類別。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | 表示值軸是否在類別之間穿過類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。讀取 **bool**。 |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | 指定日期軸上表示的最小時間單位。讀取 [TimeUnitType](../timeunittype/)。 |
| virtual **double** [get_BinWidth](./get_binwidth/)() | 當 AggregationType 屬性值設定為 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 時指定分箱寬度。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | 指定類別軸的類型。讀取 [CategoryAxisType](../categoryaxistype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| virtual **float** [get_CrossAt](./get_crossat/)() | 表示軸上垂直軸交叉的點。讀取 **float**。 |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | 表示指定軸上另一軸交叉的 CrossType。讀取 [CrossesType](../crossestype/)。 |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | 指定值軸之顯示單位的縮放值。讀取 [DisplayUnitType](../displayunittype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | 表示軸的格式。唯讀 [IAxisFormat](../iaxisformat/)。 |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | 判斷軸是否具有可見標題。讀取 **bool**。 |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | 指示軸的主要單位是否自動指派。讀取 **bool**。 |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | 指示最大值是否自動指派。讀取 **bool**。 |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | 指示軸的次要單位是否自動指派。讀取 **bool**。 |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | 指示最小值是否自動指派。讀取 **bool**。 |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | 指定自動溢位箱值。若為 false：使用 OverflowBin 屬性。 |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | 指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。讀取 **bool**。 |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | 指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。讀取 **bool**。 |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | 指定自動下溢箱值。若為 false：使用 UnderflowBin 屬性。 |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | 表示值軸的縮放類型是否為對數。讀取 **bool**。 |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | 指示格式是否為連結來源資料。讀取 **bool**。 |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | 指定是否套用溢位箱。使用 IsAutomaticOverflowBin 與 OverflowBin 來調整溢位箱值。 |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | 表示 MS PowerPoint 是否從最後到第一繪製資料點。讀取 **bool**。 |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | 指定是否套用下溢箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 來調整下溢箱值。 |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | 表示軸是否可見。讀取 **bool**。 |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | 指定標籤距離軸的距離。套用於類別或日期軸。數值必須介於 0% 與 1000% 之間。讀取 **uint16_t**。 |
| virtual **double** [get_LogBase](./get_logbase/)() | 表示對數底。預設值為 10。讀取 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | 表示圖表軸上主要格線的格式。唯讀 [IChartLinesFormat](../ichartlinesformat/)。 |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | 表示指定軸的主要刻度標記類型。讀取 [TickMarkType](../tickmarktype/)。 |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | 表示日期或值軸的主要單位。讀取 **double**。 |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | 表示日期軸的主要單位比例。讀取 [TimeUnitType](../timeunittype/)。 |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | 表示值軸的最大值。讀取 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | 表示圖表軸上次要格線的格式。唯讀 [IChartLinesFormat](../ichartlinesformat/)。 |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | 表示指定軸的次要刻度標記類型。讀取 [TickMarkType](../tickmarktype/)。 |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | 表示日期或值軸的次要單位。讀取 **double**。 |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | 表示日期軸的主要單位比例。讀取 [TimeUnitType](../timeunittype/)。 |
| virtual **double** [get_MinValue](./get_minvalue/)() | 表示值軸的最小值。讀取 **double**。 |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | 表示 [Axis](../axis/) 標籤的格式字串。讀取 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | 當 AggregationType 屬性值設定為 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 時指定分箱數量。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | 指定溢位箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | 表示軸的位置。讀取 [AxisPositionType](../axispositiontype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | 表示是否顯示主要格線。唯讀 **bool**。 |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | 表示是否顯示次要格線。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 傳回圖表文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | 表示指定軸上刻度標籤的位置。讀取 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | 表示刻度標籤的旋轉角度。讀取 **float**。 |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | 指定在已繪製標籤之間跳過多少個刻度標籤。讀取 **uint32_t**。 |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | 指定在下一個刻度標記繪製前應跳過多少個刻度標記。套用於類別或系列軸。讀取 **uint16_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | 取得軸的標題。唯讀 [IChartTitle](../icharttitle/)。 |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | 指定下溢箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的類型實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 看守物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | 表示類別軸的彙總類型（分箱）。套用於類別。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | 表示值軸是否在類別之間穿過類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。寫入 **bool**。 |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | 指定日期軸上表示的最小時間單位。寫入 [TimeUnitType](../timeunittype/)。 |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | 當 AggregationType 屬性值設定為 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 時指定分箱寬度。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | 指定類別軸的類型。寫入 [CategoryAxisType](../categoryaxistype/)。 |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | 表示軸上垂直軸交叉的點。寫入 **float**。 |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | 表示指定軸上另一軸交叉的 CrossType。寫入 [CrossesType](../crossestype/)。 |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | 指定值軸之顯示單位的縮放值。寫入 [DisplayUnitType](../displayunittype/)。 |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | 判斷軸是否具有可見標題。寫入 **bool**。 |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | 指示軸的主要單位是否自動指派。寫入 **bool**。 |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | 指示最大值是否自動指派。寫入 **bool**。 |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | 指示軸的次要單位是否自動指派。寫入 **bool**。 |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | 指示最小值是否自動指派。寫入 **bool**。 |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | 指定自動溢位箱值。若為 false：使用 OverflowBin 屬性。 |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | 指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。寫入 **bool**。 |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | 指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。寫入 **bool**。 |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | 指定自動下溢箱值。若為 false：使用 UnderflowBin 屬性。 |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | 表示值軸的縮放類型是否為對數。寫入 **bool**。 |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | 指示格式是否為連結來源資料。寫入 **bool**。 |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | 指定是否套用溢位箱。使用 IsAutomaticOverflowBin 與 OverflowBin 來調整溢位箱值。 |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | 表示 MS PowerPoint 是否從最後到第一繪製資料點。寫入 **bool**。 |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | 指定是否套用下溢箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 來調整下溢箱值。 |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | 表示軸是否可見。寫入 **bool**。 |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | 指定標籤距離軸的距離。套用於類別或日期軸。數值必須介於 0% 與 1000% 之間。寫入 **uint16_t**。 |
| virtual void [set_LogBase](./set_logbase/)(**double**) | 表示對數底。預設值為 10。寫入 **double**。 |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | 表示指定軸的主要刻度標記類型。寫入 [TickMarkType](../tickmarktype/)。 |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | 表示日期或值軸的主要單位。寫入 **double**。 |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | 表示日期軸的主要單位比例。寫入 [TimeUnitType](../timeunittype/)。 |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | 表示值軸的最大值。寫入 **double**。 |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | 表示指定軸的次要刻度標記類型。寫入 [TickMarkType](../tickmarktype/)。 |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | 表示日期或值軸的次要單位。寫入 **double**。 |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | 表示日期軸的主要單位比例。寫入 [TimeUnitType](../timeunittype/)。 |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | 表示值軸的最小值。寫入 **double**。 |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | 表示 [Axis](../axis/) 標籤的格式字串。寫入 [System::String](../../system/string/)。 |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | 當 AggregationType 屬性值設定為 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 時指定分箱數量。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | 指定溢位箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | 表示軸的位置。寫入 [AxisPositionType](../axispositiontype/)。 |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | 表示指定軸上刻度標籤的位置。寫入 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | 表示刻度標籤的旋轉角度。寫入 **float**。 |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | 指定在已繪製標籤之間跳過多少個刻度標籤。寫入 **uint32_t**。 |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | 指定在下一個刻度標記繪製前應跳過多少個刻度標記。套用於類別或系列軸。寫入 **uint16_t**。 |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | 指定下溢箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。 |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | 設定 IAxis::get(set)_CategoryAxisType 屬性，使用根據軸資料自動決定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 看守物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IFormattedTextContainer](../iformattedtextcontainer/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)