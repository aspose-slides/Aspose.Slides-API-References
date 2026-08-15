---
title: IDataLabel
second_title: Aspose.Slides C++ API 參考
description: 表示系列標籤。
type: docs
weight: 937
url: /zh-hant/aspose.slides.charts/idatalabel/
---
## IDataLabel 類別


Represents a series labels.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## 方法

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | 使用參數 "text" 中的文字初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已經初始化，則僅更改其文字。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 指定圖表元素的實際高度。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 方法以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 指定圖表元素的實際寬度。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 方法以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 指定圖表元素相對於圖表左上角的實際 x 位置（左）。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 方法以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 指定圖表元素相對於圖表左上角的實際上緣。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 方法以取得實際值。讀取 **float**。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | 取得圖表元素相對於圖表高度的上部比例。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | 傳回資料標籤的格式。唯讀 [IDataLabelFormat](../idatalabelformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | 指定圖表元素相對於圖表高度的高度比例。讀取 **float**。 |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False 表示資料標籤不可見（因此所有 Show*-旗標 (ShowValue, ...) 皆為 false）。唯讀 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | 取得圖表元素相對於圖表寬度的右側比例。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 傳回基底投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 傳回圖表文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 可包含豐富格式的文字。如果此屬性不為 null，則此格式化文字值會覆寫自動產生的文字。自動產生的文字是資料標籤、值軸的顯示單位標籤、軸標題、圖表標題、趨勢線標籤等的隱含屬性。自動產生的文字會使用 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 屬性進行格式化。唯讀 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | 取得活頁簿資料儲存格。如果 IDataLabelFormat::get(set)_ShowLabelValueFromCell 屬性為 true，則套用此設定。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | 指定圖表元素相對於圖表寬度的寬度比例。讀取 **float**。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | 指定圖表元素相對於圖表寬度的 x 位置（左）比例。讀取 **float**。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | 指定圖表元素相對於圖表高度的上緣比例。讀取 **float**。 |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | 根據 [DataLabelFormat](../datalabelformat/) 設定或 TextFrameForOverriding.Text 值傳回實際標籤文字。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。可對自訂物件進行雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual void [Hide](./hide/)() | 透過將所有 Show*-旗標 (ShowValue, ...) 設為 false，使資料標籤隱藏。此後 IsVisible 為 false。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。可對自訂型別進行克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | 指定圖表元素相對於圖表高度的高度比例。寫入 **float**。 |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | 設定工作簿資料儲存格。如果 IDataLabelFormat::get(set)_ShowLabelValueFromCell 屬性為 true，則套用此設定。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | 指定圖表元素相對於圖表寬度的寬度比例。寫入 **float**。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | 指定圖表元素相對於圖表寬度的 x 位置（左）比例。寫入 **float**。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | 指定圖表元素相對於圖表高度的上緣比例。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個範本參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。可將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [ILayoutable](../ilayoutable/)
* 類別 [IOverridableText](../ioverridabletext/)
* 類別 [IActualLayout](../iactuallayout/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)