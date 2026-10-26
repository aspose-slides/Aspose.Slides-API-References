---
title: Trendline
second_title: Aspose.Slides for C++ API 參考
description: 類別表示圖表系列的趨勢線
type: docs
weight: 1366
url: /zh-hant/aspose.slides.charts/trendline/
---
## 趨勢線類別

類別表示圖表系列的趨勢線

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | 使用參數 \"text\" 中的文字初始化 TextFrameForOverriding。如已初始化 TextFrameForOverriding，則直接更改其文字。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **double** [get_Backward](./get_backward/)() override | 指定趨勢線在所屬系列資料之前延伸的類別（或散佈圖上的單位）數量。於散佈圖與非散佈圖上，該值必須為任何非負值。讀取 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 傳回父圖表。唯讀 [IChart](../ichart/)。 |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | 指定是否在圖表上（與 Rsquaredvalue 同一標籤）顯示趨勢線方程式。讀取 **bool**。 |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | 指定是否在圖表上（與方程式同一標籤）顯示趨勢線的 R 平方值。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 表示趨勢線的格式。讀取 [IFormat](../iformat/)。 |
| **double** [get_Forward](./get_forward/)() override | 指定趨勢線在所屬系列資料之後延伸的類別（或散佈圖上的單位）數量。於散佈圖與非散佈圖上，該值必須為任何非負值。讀取 **double**。 |
| **double** [get_Intercept](./get_intercept/)() override | 指定趨勢線與 y 軸交叉的值。僅在趨勢線類型為 exp、linear 或 poly 時支援此屬性。讀取 **double**。 |
| **uint8_t** [get_Order](./get_order/)() override | 指定多項式趨勢線的階數。對其他趨勢線類型則忽略。值必須介於 2 到 6 之間。讀取 **uint8_t**。 |
| **uint8_t** [get_Period](./get_period/)() override | 指定移動平均趨勢線的週期。對其他趨勢線變體則忽略。值必須介於 2 到 255 之間。讀取 **uint8_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | 表示與此趨勢線相關的圖例項目。唯讀 [ILegendEntryProperties](../ilegendentryproperties/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 傳回文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | 可以包含富格式文字。若此屬性不為 null，則此格式化文字會覆寫資料標籤的自動產生文字。資料標籤的自動產生文字指由 ShowSeriesName、ShowValue… 等屬性管理，並以 TextFormatManager.TextFormat 屬性格式化的文字。唯讀 [ITextFrame](../../aspose.slides/itextframe/)。 |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | 取得趨勢線的名稱。讀取 [System::String](../../system/string/)。 |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | 取得趨勢線的類型。讀取 [Charts::TrendlineType](../trendlinetype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對 string 與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Backward](./set_backward/)(**double**) override | 指定趨勢線在所屬系列資料之前延伸的類別（或散佈圖上的單位）數量。於散佈圖與非散佈圖上，該值必須為任何非負值。寫入 **double**。 |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | 指定是否在圖表上（與 Rsquaredvalue 同一標籤）顯示趨勢線方程式。寫入 **bool**。 |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | 指定是否在圖表上（與方程式同一標籤）顯示趨勢線的 R 平方值。寫入 **bool**。 |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | 表示趨勢線的格式。寫入 [IFormat](../iformat/)。 |
| void [set_Forward](./set_forward/)(**double**) override | 指定趨勢線在所屬系列資料之後延伸的類別（或散佈圖上的單位）數量。於散佈圖與非散佈圖上，該值必須為任何非負值。寫入 **double**。 |
| void [set_Intercept](./set_intercept/)(**double**) override | 指定趨勢線與 y 軸交叉的值。僅在趨勢線類型為 exp、linear 或 poly 時支援此屬性。寫入 **double**。 |
| void [set_Order](./set_order/)(**uint8_t**) override | 指定多項式趨勢線的階數。對其他趨勢線類型則忽略。值必須介於 2 到 6 之間。寫入 **uint8_t**。 |
| void [set_Period](./set_period/)(**uint8_t**) override | 指定移動平均趨勢線的週期。對其他趨勢線變體則忽略。值必須介於 2 到 255 之間。寫入 **uint8_t**。 |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | 設定趨勢線的名稱。寫入 [System::String](../../system/string/)。 |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | 設定趨勢線的類型。寫入 [Charts::TrendlineType](../trendlinetype/)。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [DomObject](../../aspose.slides/domobject/)
* 類別 [ITrendline](../itrendline/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)