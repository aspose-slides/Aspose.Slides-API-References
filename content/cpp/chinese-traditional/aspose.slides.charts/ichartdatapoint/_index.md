---
title: IChartDataPoint
second_title: Aspose.Slides for C++ API 參考
description: 表示系列資料點。
type: docs
weight: 677
url: /zh-hant/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint 類別

表示系列資料點。

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 指定圖表元素的實際高度。呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 指定圖表元素的實際寬度。呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 指定圖表元素相對於圖表左上角的實際 x 位置（左）。呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 指定圖表元素相對於圖表左上角的實際上緣。呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | 返回圖表資料點的氣泡大小。唯讀 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | 返回圖表資料點的顏色值。用於地圖圖表。唯讀 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | 返回指定索引處的資料點層級。用於 Treeamp 和 Sunburst 系列。資料點層級的索引從 0 開始。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | 返回資料點層級的容器。用於 Treeamp 和 Sunburst 系列。資料點層級的索引從 0 開始。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | 表示自訂值類型情況下系列誤差棒的值。唯讀 [IErrorBarsCustomValues](../ierrorbarscustomvalues/)。 |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | 指定資料點應從餅圖中心移動的距離。讀取 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 表示格式屬性。讀取 [IFormat](../iformat/)。 |
| virtual **uint32_t** [get_Index](./get_index/)() | 決定此資料點適用於父項子集合中的哪一個。讀取 **uint32_t**。 |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | 指定當值為負時，資料點應反轉其顏色。讀取 **bool**。 |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | 指定氣泡套用 3D 效果。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | 表示圖表資料點的標籤。唯讀 [IDataLabel](../idatalabel/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | 指定資料標記。唯讀 [IMarker](../imarker/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 屬於以下圖表類型的對應圖例項目之屬性：[ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/)。唯讀 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | 將資料點設定為總計。僅適用於 Waterfall 系列類型。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | 返回圖表資料點的尺寸值。用於 Treemap 和 Sunburst 圖表。唯讀 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | 返回圖表資料點的值。唯讀 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | 返回圖表資料點的 x 值。唯讀 [IStringOrDoubleChartValue](../istringordoublechartvalue/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | 返回圖表資料點的 y 值。唯讀 [IDoubleChartValue](../idoublechartvalue/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | 返回依據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性與圖表樣式自動決定的資料點顏色。若 FillType 為 NotDefined，則預設使用此顏色。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 「is」運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指定運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| virtual void [Remove](./remove/)() | 從圖表系列中移除 DataPoint。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | 指定資料點應從餅圖中心移動的距離。寫入 **int32_t**。 |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | 表示格式屬性。寫入 [IFormat](../iformat/)。 |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | 指定當值為負時，資料點應反轉其顏色。寫入 **bool**。 |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | 指定氣泡套用 3D 效果。寫入 **bool**。 |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | 將資料點設定為總計。僅適用於 Waterfall 系列類型。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IActualLayout](../iactuallayout/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)