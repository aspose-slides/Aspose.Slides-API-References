---
title: ITrendline
second_title: Aspose.Slides for C++ API 參考文件
description: 類別代表圖表系列的趨勢線
type: docs
weight: 1223
url: /zh-hant/aspose.slides.charts/itrendline/
---
## ITrendline 類別

類別代表圖表系列的趨勢線

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | 使用參數 \"text\" 中的文字初始化 TextFrameForOverriding。若 TextFrameForOverriding 已經初始化，則僅更改其文字。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **double** [get_Backward](./get_backward/)() | 指定趨勢線在所屬系列資料之前延伸的類別數（或散佈圖上的單位）。於散佈圖與非散佈圖上，此值應為任何非負值。讀取 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | 指定是否在圖表上顯示趨勢線方程式（與 R 平方值相同的標籤中）。讀取 **bool**。 |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | 指定是否在圖表上顯示趨勢線的 R 平方值（與方程式相同的標籤中）。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 代表趨勢線的格式。讀取 [IFormat](../iformat/)。 |
| virtual **double** [get_Forward](./get_forward/)() | 指定趨勢線在所屬系列資料之後延伸的類別數（或散佈圖上的單位）。於散佈圖與非散佈圖上，此值應為任何非負值。讀取 **double**。 |
| virtual **double** [get_Intercept](./get_intercept/)() | 指定趨勢線與 y 軸交叉的值。此屬性僅在趨勢線類型為 exp、linear 或 poly 時受支援。讀取 **double**。 |
| virtual **uint8_t** [get_Order](./get_order/)() | 指定多項式趨勢線的階數。對其他趨勢線類型會被忽略。值必須介於 2 與 6 之間。讀取 **uint8_t**。 |
| virtual **uint8_t** [get_Period](./get_period/)() | 指定移動平均趨勢線的週期。對其他趨勢線變體會被忽略。值必須介於 2 與 255 之間。讀取 **uint8_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | 代表與此趨勢線相關的圖例項目。唯讀 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 傳回圖表文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | 可包含富格式文字。若此屬性非 null，則此格式化文字會覆寫自動產生的文字。自動產生的文字是資料標籤、值軸的顯示單位標籤、軸標題、圖表標題、趨勢線標籤的隱含屬性。自動產生的文字會以 [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) 屬性格式化。唯讀 [ITextFrame](../../aspose.slides/itextframe/)。 |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | 取得趨勢線的名稱。讀取 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | 取得趨勢線的類型。讀取 [TrendlineType](../trendlinetype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式之鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 把關物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 以參考方式比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_Backward](./set_backward/)(**double**) | 指定趨勢線在所屬系列資料之前延伸的類別數（或散佈圖上的單位）。於散佈圖與非散佈圖上，此值應為任何非負值。寫入 **double**。 |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | 指定是否在圖表上顯示趨勢線的方程式（與 R 平方值相同的標籤中）。寫入 **bool**。 |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | 指定是否在圖表上顯示趨勢線的 R 平方值（與方程式相同的標籤中）。寫入 **bool**。 |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | 代表趨勢線的格式。寫入 [IFormat](../iformat/)。 |
| virtual void [set_Forward](./set_forward/)(**double**) | 指定趨勢線在所屬系列資料之後延伸的類別數（或散佈圖上的單位）。於散佈圖與非散佈圖上，此值應為任何非負值。寫入 **double**。 |
| virtual void [set_Intercept](./set_intercept/)(**double**) | 指定趨勢線與 y 軸交叉的值。此屬性僅在趨勢線類型為 exp、linear 或 poly 時受支援。寫入 **double**。 |
| virtual void [set_Order](./set_order/)(**uint8_t**) | 指定多項式趨勢線的階數。對其他趨勢線類型會被忽略。值必須介於 2 與 6 之間。寫入 **uint8_t**。 |
| virtual void [set_Period](./set_period/)(**uint8_t**) | 指定移動平均趨勢線的週期。對其他趨勢線變體會被忽略。值必須介於 2 與 255 之間。寫入 **uint8_t**。 |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | 設定趨勢線的名稱。寫入 [System::String](../../system/string/)。 |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | 設定趨勢線的類型。寫入 [TrendlineType](../trendlinetype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式之解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 把關物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [IOverridableText](../ioverridabletext/)
* 命名空間 [Aspose::Slides::Charts](../)
* 程式庫 [Aspose.Slides](../../)