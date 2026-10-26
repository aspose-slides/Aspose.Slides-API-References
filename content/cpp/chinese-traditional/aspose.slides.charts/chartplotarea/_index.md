---
title: ChartPlotArea
second_title: Aspose.Slides for C++ API 參考手冊
description: 表示圖表應繪製的矩形。
type: docs
weight: 248
url: /zh-hant/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea 類別

Represents rectangle where chart should be plotted.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包含 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包含 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | 指定圖表元件的實際高度。於取得實際值前先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。讀取 **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 指定圖表元件的實際寬度。於取得實際值前先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。讀取 **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | 指定圖表元件相對於圖表左上角的實際 x 位置（左側）。於取得實際值前先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。讀取 **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | 指定圖表元件相對於圖表左上角的實際上緣。於取得實際值前先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/)。讀取 **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 底部。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/)。唯讀 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 傳回繪圖區的格式。唯讀 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | 傳回繪圖區邊框的高度，作為圖表高度的比例（從 0 到 1）。讀取 **float**。 |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | 定義位置的計算方式：true – 自動計算；由 X、Y、Width、Height 屬性定義。唯讀 **bool**。 |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | 如果手動定義繪圖區的版面配置，此屬性指定是依其內部（不含座標軸與座標軸標籤）或外部（含座標軸與座標軸標籤）進行版面配置。讀取 [LayoutTargetType](../layouttargettype/)。 |
| **float** [get_Right](./get_right/)() override | 右側。唯讀 **float**。 |
| **float** [get_Width](./get_width/)() override | 傳回繪圖區邊框的寬度，作為圖表寬度的比例（從 0 到 1）。讀取 **float**。 |
| **float** [get_X](./get_x/)() override | 傳回繪圖區邊框左上角的 x 座標，作為圖表寬度的比例（從 0 到 1）。讀取 **float**。 |
| **float** [get_Y](./get_y/)() override | 傳回繪圖區邊框左上角的 y 座標，作為圖表高度的比例（從 0 到 1）。讀取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的型別實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Height](./set_height/)(**float**) override | 設定繪圖區邊框的高度，作為圖表高度的比例（從 0 到 1）。寫入 **float**。 |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | 如果手動定義繪圖區的版面配置，此屬性指定是依其內部（不含座標軸與座標軸標籤）或外部（含座標軸與座標軸標籤）進行版面配置。寫入 [LayoutTargetType](../layouttargettype/)。 |
| void [set_Width](./set_width/)(**float**) override | 設定繪圖區邊框的寬度，作為圖表寬度的比例（從 0 到 1）。寫入 **float**。 |
| void [set_X](./set_x/)(**float**) override | 設定繪圖區邊框左上角的 x 座標，作為圖表寬度的比例（從 0 到 1）。寫入 **float**。 |
| void [set_Y](./set_y/)(**float**) override | 設定繪圖區邊框左上角的 y 座標，作為圖表高度的比例（從 0 到 1）。寫入 **float**。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [DomObject](../../aspose.slides/domobject/)
* 類別 [IChartPlotArea](../ichartplotarea/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)