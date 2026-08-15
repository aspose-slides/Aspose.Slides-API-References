---
title: ChartTitle
second_title: Aspose.Slides C++ API 參考
description: 代表圖表標題屬性。
type: docs
weight: 326
url: /zh-hant/aspose.slides.charts/charttitle/
---
## ChartTitle 類別

代表圖表標題屬性。

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | 使用 paramener \"text\" 中的文字初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已經初始化，則僅更改其文字。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | 指定圖表元素的實際高度。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 指定圖表元素的實際寬度。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | 指定圖表元素相對於圖表左上角的實際 x 位置（左側）。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | 指定圖表元素相對於圖表左上角的實際上緣。請先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 底部。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 返回父圖表。唯讀 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 返回標題的填充、線條、效果樣式。唯讀 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | 返回標題的高度，作為圖表高度的比例。讀取 **float**。 |
| **bool** [get_Overlay](./get_overlay/)() override | 判斷是否允許其他圖表元素與標題重疊。讀取 **bool**。 |
| **float** [get_Right](./get_right/)() override | 右側。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 返回文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | 可包含富格式文字。如果此屬性不為 null，則此格式化文字值會覆蓋自動產生的文字。自動產生的文字是資料標籤、數值軸的顯示單位標籤、軸標題、圖表標題、趨勢線標籤的隱含屬性。自動產生的文字以 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 屬性進行格式化。唯讀 [ITextFrame](../../aspose.slides/itextframe/)。 |
| **float** [get_Width](./get_width/)() override | 返回標題的寬度，作為圖表寬度的比例。讀取 **float**。 |
| **float** [get_X](./get_x/)() override | 返回標題的 x 座標，作為圖表寬度的比例。讀取 **float**。 |
| **float** [get_Y](./get_y/)() override | 返回標題的 y 座標，作為圖表高度的比例。讀取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆功能。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [set_Height](./set_height/)(**float**) override | 設定標題的高度，作為圖表高度的比例。寫入 **float**。 |
| void [set_Overlay](./set_overlay/)(**bool**) override | 決定是否允許其他圖表元素與標題重疊。寫入 **bool**。 |
| void [set_Width](./set_width/)(**float**) override | 設定標題的寬度，作為圖表寬度的比例。寫入 **float**。 |
| void [set_X](./set_x/)(**float**) override | 設定標題的 x 座標，作為圖表寬度的比例。寫入 **float**。 |
| void [set_Y](./set_y/)(**float**) override | 設定標題的 y 座標，作為圖表高度的比例。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並返回共享參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構子。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IChartTitle](../icharttitle/)
* 類別 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)