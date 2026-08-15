---
title: Legend
second_title: Aspose.Slides for C++ API 參考
description: 表示圖表的圖例屬性。
type: docs
weight: 1262
url: /zh-hant/aspose.slides.charts/legend/
---
## Legend 類別

表示圖表的圖例屬性。

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **float** [get_ActualHeight](./get_actualheight/)() override | 指定圖表元素的實際高度。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_ActualWidth](./get_actualwidth/)() override | 指定圖表元素的實際寬度。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_ActualX](./get_actualx/)() override | 指定圖表元素相對於圖表左上角的實際 x 位置（左）。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_ActualY](./get_actualy/)() override | 指定圖表元素相對於圖表左上角的實際上邊緣。先呼叫方法 [IChart::ValidateChartLayout](../ichart/validatechartlayout/) 以取得實際值。讀取 **float**。 |
| **float** [get_Bottom](./get_bottom/)() override | 底部。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | 取得圖例條目。唯讀 [ILegendEntryCollection](../ilegendentrycollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | 取得對應於圖表中指定索引之資料點之圖例項目的屬性。對於圖表類型：bar-of-pie、exploded pie、exploded pie 3D、pie、pie 3D、pie-of-pie，資料點取自第一個序列。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 傳回圖例的格式。唯讀 [IFormat](../iformat/)。 |
| **float** [get_Height](./get_height/)() override | 傳回圖例的高度，作為圖表高度的比例。讀取 **float**。 |
| **bool** [get_Overlay](./get_overlay/)() override | 決定是否允許其他圖表元素與圖例重疊。讀取 **bool**。 |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | 指定圖例在圖表上的位置。X、Y、Width、Heigt 屬性的非 NaN 值會覆寫此屬性的效果。讀取 [LegendPositionType](../legendpositiontype/)。 |
| **float** [get_Right](./get_right/)() override | 右側。唯讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| **float** [get_Width](./get_width/)() override | 傳回圖例的寬度，作為圖表寬度的比例。讀取 **float**。 |
| **float** [get_X](./get_x/)() override | 傳回圖例的 x 座標，作為圖表寬度的比例。讀取 **float**。 |
| **float** [get_Y](./get_y/)() override | 傳回圖例的 y 座標，作為圖表高度的比例。讀取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的對應。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的對應。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的對應。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於 string 與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| void [set_Height](./set_height/)(**float**) override | 設定圖例的高度，作為圖表高度的比例。寫入 **float**。 |
| void [set_Overlay](./set_overlay/)(**bool**) override | 決定是否允許其他圖表元素與圖例重疊。寫入 **bool**。 |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | 指定圖例在圖表上的位置。X、Y、Width、Heigt 屬性的非 NaN 值會覆寫此屬性的效果。寫入 [LegendPositionType](../legendpositiontype/)。 |
| void [set_Width](./set_width/)(**float**) override | 設定圖例的寬度，作為圖表寬度的比例。寫入 **float**。 |
| void [set_X](./set_x/)(**float**) override | 設定圖例的 x 座標，作為圖表寬度的比例。寫入 **float**。 |
| void [set_Y](./set_y/)(**float**) override | 設定圖例的 y 座標，作為圖表高度的比例。寫入 **float**。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的對應。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [DomObject](../../aspose.slides/domobject/)
* 類別 [ILegend](../ilegend/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)