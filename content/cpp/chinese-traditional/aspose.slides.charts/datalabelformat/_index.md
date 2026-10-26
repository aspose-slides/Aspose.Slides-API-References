---
title: DataLabelFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示 DataLabel 的格式選項。
type: docs
weight: 391
url: /zh-hant/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat 類別

表示 [DataLabel](../datalabel/) 的格式選項。

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部用途。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | 表示資料標籤的格式。唯讀 [IFormat](../iformat/)。 |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | 讀取 **bool**。 |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | 表示 DataLabels 物件的格式字串。讀取 [System::String](../../system/string/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | 傳回 Parent_Immediate 物件。唯讀 [IDOMObject](../../aspose.slides/idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 傳回父層 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。唯讀 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | 表示資料標籤的位置。讀取 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | 設定或傳回表示圖表上資料標籤使用之分隔符號的 Variant。讀取 [System::String](../../system/string/)。 |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | 表示指定圖表的資料標籤氣泡大小值顯示行為。True 顯示氣泡大小值。False 隱藏。讀取 **bool**。 |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | 表示指定圖表的資料標籤類別名稱顯示行為。True 顯示類別名稱。False 隱藏。讀取 **bool**。 |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | 決定指定圖表的資料標籤將以資料標註或資料標籤形式顯示。 |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | 表示指定圖表的資料標籤儲存格值顯示行為。True 顯示儲存格值。False 隱藏。讀取 **bool**。 |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | 表示指定圖表的資料標籤指示線顯示行為。True 顯示指示線。False 隱藏。讀取 **bool**。 |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | 表示指定圖表的資料標籤圖例鍵顯示行為。若圖例鍵可見則為 True。讀取 **bool**。 |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | 表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。讀取 **bool**。 |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | 傳回布林值以指示圖表上資料標籤的系列名稱顯示行為。True 顯示系列名稱。False 隱藏。讀取 **bool**。 |
| **bool** [get_ShowValue](./get_showvalue/)() override | 表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | 傳回圖表文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | 傳回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的型別實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指定運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 的情況，[Object::ReferenceEquals](../../system/object/referenceequals/) 的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，處理字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定值。 |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | 寫入 **bool**。 |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | 表示 DataLabels 物件的格式字串。寫入 [System::String](../../system/string/)。 |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | 表示資料標籤的位置。寫入 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | 設定或傳回表示圖表上資料標籤使用之分隔符號的 Variant。寫入 [System::String](../../system/string/)。 |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | 表示指定圖表的資料標籤氣泡大小值顯示行為。True 顯示氣泡大小值。False 隱藏。寫入 **bool**。 |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | 表示指定圖表的資料標籤類別名稱顯示行為。True 顯示類別名稱。False 隱藏。寫入 **bool**。 |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | 決定指定圖表的資料標籤將以資料標註或資料標籤形式顯示。 |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | 表示指定圖表的資料標籤儲存格值顯示行為。True 顯示儲存格值。False 隱藏。寫入 **bool**。 |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | 表示指定圖表的資料標籤指示線顯示行為。True 顯示指示線。False 隱藏。寫入 **bool**。 |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | 表示指定圖表的資料標籤圖例鍵顯示行為。若圖例鍵可見則為 True。寫入 **bool**。 |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | 表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。寫入 **bool**。 |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | 設定布林值以指示圖表上資料標籤的系列名稱顯示行為。True 顯示系列名稱。False 隱藏。寫入 **bool**。 |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | 表示指定圖表的資料標籤百分比值顯示行為。True 顯示百分比值。False 隱藏。寫入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個範本參數為弱指標（而非共用指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參考

* 類別 [PVIObject](../../aspose.slides/pviobject/)
* 類別 [IDataLabelFormat](../idatalabelformat/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)