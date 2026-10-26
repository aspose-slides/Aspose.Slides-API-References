---
title: Axis
second_title: Aspose.Slides for C++ API 參考
description: 封裝代表圖表軸的物件。
type: docs
weight: 14
url: /zh-hant/aspose.slides.charts/axis/
---
## Axis 類別

封裝代表圖表軸的物件。

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | 指定軸的實際主要單位。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | 指定軸的實際主要單位比例。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | 指定軸的實際最大值。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | 指定軸的實際次要單位。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | 指定軸的實際次要單位比例。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | 指定軸的實際最小值。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。 |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | 表示類別軸的彙總類型（分箱）。適用於類別。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | 表示值軸是否在類別之間跨過類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。讀取 **bool**。 |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | 指定日期軸上表示的最小時間單位。讀取 [TimeUnitType](../timeunittype/)。 |
| **double** [get_BinWidth](./get_binwidth/)() override | 在 AggregationType 屬性值設為 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 時指定分箱寬度。適用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | 指定類別軸的類型。讀取 [Charts::CategoryAxisType](../categoryaxistype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 傳回父圖表。唯讀 [IChart](../ichart/)。 |
| **float** [get_CrossAt](./get_crossat/)() override | 表示軸上與垂直軸相交的點。讀取 **float**。 |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | 表示指定軸上其他軸相交的 CrossType。讀取 [CrossesType](../crossestype/)。 |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | 指定值軸顯示單位的縮放值。讀取 [DisplayUnitType](../displayunittype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | 表示軸的格式。唯讀 [IAxisFormat](../iaxisformat/)。 |
| **bool** [get_HasTitle](./get_hastitle/)() override | 判斷軸是否具有可見標題。讀取 **bool**。 |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | 指示軸的主要單位是否自動指派。讀取 **bool**。 |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | 指示最大值是否自動指派。讀取 **bool**。 |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | 指示軸的次要單位是否自動指派。讀取 **bool**。 |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | 指示最小值是否自動指派。讀取 **bool**。 |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | 指定自動溢位分箱值。若為 false：使用 OverflowBin 屬性。 |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | 指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。讀取 **bool**。 |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | 指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。讀取 **bool**。 |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | 指定自動欠位分箱值。若為 false：使用 UnderflowBin 屬性。 |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | 表示值軸的刻度類型是否為對數。讀取 **bool**。 |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | 指示格式是否為連結來源資料。讀取 **bool**。 |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | 指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 調整溢位分箱值。 |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | 表示 MS PowerPoint 是否從最後到第一個繪製資料點。讀取 **bool**。 |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | 指定是否套用欠位分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 調整欠位分箱值。 |
| **bool** [get_IsVisible](./get_isvisible/)() override | 表示軸是否可見。讀取 **bool**。 |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | 指定標籤與軸的距離。適用於類別或日期軸。值必須介於 0% 與 1000% 之間。讀取 **uint16_t**。 |
| **double** [get_LogBase](./get_logbase/)() override | 表示對數底數。預設值為 10。讀取 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | 表示圖表軸上主要格線的格式。唯讀 [IChartLinesFormat](../ichartlinesformat/)。 |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | 表示指定軸的主要刻度標記類型。讀取 [TickMarkType](../tickmarktype/)。 |
| **double** [get_MajorUnit](./get_majorunit/)() override | 表示日期或值軸的主要單位。讀取 **double**。 |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | 表示日期軸的主要單位比例。讀取 [TimeUnitType](../timeunittype/)。 |
| **double** [get_MaxValue](./get_maxvalue/)() override | 表示值軸的最大值。讀取 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | 表示圖表軸上次要格線的格式。唯讀 [IChartLinesFormat](../ichartlinesformat/)。 |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | 表示指定軸的次要刻度標記類型。讀取 [TickMarkType](../tickmarktype/)。 |
| **double** [get_MinorUnit](./get_minorunit/)() override | 表示日期或值軸的次要單位。讀取 **double**。 |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | 表示日期軸的主要單位比例。讀取 [TimeUnitType](../timeunittype/)。 |
| **double** [get_MinValue](./get_minvalue/)() override | 表示值軸的最小值。讀取 **double**。 |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | 表示 [Axis](./) 標籤的格式字串。讀取 [System::String](../../system/string/)。 |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | 在 AggregationType 屬性值設為 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 時指定分箱數量。適用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| **double** [get_OverflowBin](./get_overflowbin/)() override | 指定溢位分箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | 表示軸的位置。讀取 [AxisPositionType](../axispositiontype/)。 |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | 若要隱藏主要格線，將 [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() 設為 [FillType::NoFill](../../aspose.slides/filltype/)。唯讀 **bool**。 |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | 若要隱藏次要格線，將 [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() 設為 [FillType::NoFill](../../aspose.slides/filltype/)。唯讀 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 表示文字的格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | 表示指定軸上刻度標籤的位置。讀取 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | 表示刻度標籤的旋轉角度。讀取 **float**。 |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | 指定在已繪製的標籤之間要跳過多少個刻度標籤。適用於類別或系列軸。讀取 **uint32_t**。 |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。適用於類別或系列軸。讀取 **uint16_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | 取得軸的標題。唯讀 [IChartTitle](../icharttitle/)。 |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | 指定欠位分箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。允許自訂物件的雜湊運算。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允許自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許為子類別進行複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許為子類別進行複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串和 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | 表示類別軸的彙總類型（分箱）。適用於類別。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | 表示值軸是否在類別之間跨過類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。寫入 **bool**。 |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | 指定日期軸上表示的最小時間單位。寫入 [TimeUnitType](../timeunittype/)。 |
| void [set_BinWidth](./set_binwidth/)(**double**) override | 在 AggregationType 屬性值設為 [AxisAggregationType::ByBinWidth](../axisaggregationtype/) 時指定分箱寬度。適用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | 指定類別軸的類型。寫入 [Charts::CategoryAxisType](../categoryaxistype/)。 |
| void [set_CrossAt](./set_crossat/)(**float**) override | 表示軸上與垂直軸相交的點。寫入 **float**。 |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | 表示指定軸上其他軸相交的 CrossType。寫入 [CrossesType](../crossestype/)。 |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | 指定值軸顯示單位的縮放值。寫入 [DisplayUnitType](../displayunittype/)。 |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | 判斷軸是否具有可見標題。寫入 **bool**。 |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | 指示軸的主要單位是否自動指派。寫入 **bool**。 |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | 指示最大值是否自動指派。寫入 **bool**。 |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | 指示軸的次要單位是否自動指派。寫入 **bool**。 |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | 指示最小值是否自動指派。寫入 **bool**。 |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | 指定自動溢位分箱值。若為 false：使用 OverflowBin 屬性。 |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | 指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。寫入 **bool**。 |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | 指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。寫入 **bool**。 |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | 指定自動欠位分箱值。若為 false：使用 UnderflowBin 屬性。 |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | 表示值軸的刻度類型是否為對數。寫入 **bool**。 |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | 指示格式是否為連結來源資料。寫入 **bool**。 |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | 指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 調整溢位分箱值。 |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | 表示 MS PowerPoint 是否從最後到第一個繪製資料點。寫入 **bool**。 |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | 指定是否套用欠位分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 調整欠位分箱值。 |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | 表示軸是否可見。寫入 **bool**。 |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | 指定標籤與軸的距離。適用於類別或日期軸。值必須介於 0% 與 1000% 之間。寫入 **uint16_t**。 |
| void [set_LogBase](./set_logbase/)(**double**) override | 表示對數底數。預設值為 10。寫入 **double**。 |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | 表示指定軸的主要刻度標記類型。寫入 [TickMarkType](../tickmarktype/)。 |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | 表示日期或值軸的主要單位。寫入 **double**。 |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | 表示日期軸的主要單位比例。寫入 [TimeUnitType](../timeunittype/)。 |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | 表示值軸的最大值。寫入 **double**。 |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | 表示指定軸的次要刻度標記類型。寫入 [TickMarkType](../tickmarktype/)。 |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | 表示日期或值軸的次要單位。寫入 **double**。 |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | 表示日期軸的主要單位比例。寫入 [TimeUnitType](../timeunittype/)。 |
| void [set_MinValue](./set_minvalue/)(**double**) override | 表示值軸的最小值。寫入 **double**。 |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | 表示 [Axis](./) 標籤的格式字串。寫入 [System::String](../../system/string/)。 |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | 在 AggregationType 屬性值設為 [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) 時指定分箱數量。適用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。 |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | 指定溢位分箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。 |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | 表示軸的位置。寫入 [AxisPositionType](../axispositiontype/)。 |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | 表示指定軸上刻度標籤的位置。寫入 [TickLabelPositionType](../ticklabelpositiontype/)。 |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | 表示刻度標籤的旋轉角度。寫入 **float**。 |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | 指定在已繪製的標籤之間要跳過多少個刻度標籤。適用於類別或系列軸。寫入 **uint32_t**。 |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。適用於類別或系列軸。寫入 **uint16_t**。 |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | 指定欠位分箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。 |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | 設定 IAxis::get(set)_CategoryAxisType 屬性，使用根據軸資料自動決定的值。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 構造式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [DomObject](../../aspose.slides/domobject/)
* 類別 [IAxis](../iaxis/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)