---
title: IChartTitle
second_title: Aspose.Slides for C++ API 參考文件
description: 代表圖表標題屬性。
type: docs
weight: 911
url: /zh-hant/aspose.slides.charts/icharttitle/
---
## IChartTitle 類別


代表圖表標題屬性。

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | 使用參數 \"text\" 中的文字初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已經初始化，則僅更改其文字。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | 指定圖表元件的實際高度。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | 指定圖表元件的實際寬度。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | 指定圖表元件相對於圖表左上角的實際 x 位置（左）。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | 指定圖表元件相對於圖表左上角的實際上緣。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | 取得圖表元件上緣相對於圖表高度的比例。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 傳回標題的填滿、線條、效果樣式。唯讀 [IFormat](../iformat/)。 |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | 指定圖表元件高度相對於圖表高度的比例。讀取 **float**。 |
| virtual **bool** [get_Overlay](./get_overlay/)() | 決定是否允許其他圖表元件覆蓋標題。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | 取得圖表元件右側相對於圖表寬度的比例。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 傳回圖表文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 可以包含豐富格式化的文字。如果此屬性不為 null，則此格式化文字值會覆寫自動產生的文字。自動產生的文字是資料標籤、值軸的顯示單位標籤、軸標題、圖表標題、趨勢線標籤的隱含屬性。自動產生的文字會以 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 屬性進行格式化。唯讀 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | 指定圖表元件寬度相對於圖表寬度的比例。讀取 **float**。 |
| virtual **float** [get_X](../ilayoutable/get_x/)() | 指定圖表元件 x 位置（左）相對於圖表寬度的比例。讀取 **float**。 |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | 指定圖表元件上緣相對於圖表高度的比例。讀取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似功能。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指定運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | 指定圖表元件高度相對於圖表高度的比例。寫入 **float**。 |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | 決定是否允許其他圖表元件覆蓋標題。寫入 **bool**。 |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | 指定圖表元件寬度相對於圖表寬度的比例。寫入 **float**。 |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | 指定圖表元件 x 位置（左）相對於圖表寬度的比例。寫入 **float**。 |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | 指定圖表元件上緣相對於圖表高度的比例。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [ILayoutable](../ilayoutable/)
* 類別 [IOverridableText](../ioverridabletext/)
* 類別 [IActualLayout](../iactuallayout/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)