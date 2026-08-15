---
title: DataLabel
second_title: Aspose.Slides for C++ API 參考
description: 代表系列標籤。
type: docs
weight: 365
url: /zh-hant/aspose.slides.charts/datalabel/
---
## DataLabel 類別

代表系列標籤。

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | 使用參數 "text" 中的文字初始化 TextFrameForOverriding。若 TextFrameForOverriding 已經初始化，則僅更改其文字。 |
| [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | 建立 [DataLabel](./) 類別的新執行個體。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型的物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | 指定圖表元素的實際高度。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 取得實際值。讀取 **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 指定圖表元素的實際寬度。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 取得實際值。讀取 **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | 指定圖表元素相對於圖表左上角的實際 X 位置（左側）。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 取得實際值。讀取 **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | 指定圖表元素相對於圖表左上角的實際上緣。先呼叫 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 取得實際值。讀取 **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 底部。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 傳回父圖表。唯讀 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | 傳回資料標籤格式。唯讀 [IDataLabelFormat](../idatalabelformat/)。 |
| **float** [get_Height](./get_height/)() override | 傳回標題高度佔圖表高度的比例。讀取 **float**。 |
| **bool** [get_IsVisible](./get_isvisible/)() override | False 表示資料標籤不可見（因此所有 Show* 旗標（ShowValue 等）皆為 false）。唯讀 **bool**。 |
| **float** [get_Right](./get_right/)() override | 右側。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 傳回文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | 可以包含富格式文字。若此屬性非 null，則此格式化文字值會覆寫資料標籤的自動產生文字。資料標籤的自動產生文字指的是由 ShowSeriesName、ShowValue 等屬性管理，並使用 TextFormatManager.TextFormat 屬性格式化的文字。唯讀 [ITextFrame](../../aspose.slides/itextframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | 取得工作簿資料儲存格。當 IDataLabelFormat::get(set)_ShowLabelValueFromCell 屬性為 true 時套用。 |
| **float** [get_Width](./get_width/)() override | 傳回標題寬度佔圖表寬度的比例。讀取 **float**。 |
| **float** [get_X](./get_x/)() override | 傳回標題 X 座標佔圖表寬度的比例。讀取 **float**。 |
| **float** [get_Y](./get_y/)() override | 傳回標題 Y 座標佔圖表高度的比例。讀取 **float**。 |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | 傳回根據 [DataLabelFormat](../datalabelformat/) 設定或 [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() 值的實際標籤文字。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。允許自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| void [Hide](./hide/)() override | 透過將所有 Show* 旗標（ShowValue 等）設為 false，使資料標籤隱藏。IsVisible 之後會為 false。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的型別實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允許克隆自訂型別。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於 string 與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Height](./set_height/)(**float**) override | 設定標題高度佔圖表高度的比例。寫入 **float**。 |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | 設定工作簿資料儲存格。當 IDataLabelFormat::get(set)_ShowLabelValueFromCell 屬性為 true 時套用。 |
| void [set_Width](./set_width/)(**float**) override | 設定標題寬度佔圖表寬度的比例。寫入 **float**。 |
| void [set_X](./set_x/)(**float**) override | 設定標題 X 座標佔圖表寬度的比例。寫入 **float**。 |
| void [set_Y](./set_y/)(**float**) override | 設定標題 Y 座標佔圖表高度的比例。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫，請改用智能指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少且回傳共享參考計數。不應直接呼叫，請改用智能指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫，請改用智能指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫，請改用智能指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IDataLabel](../idatalabel/)
* 類別 [IDOMObject](../../aspose.slides/idomobject/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)