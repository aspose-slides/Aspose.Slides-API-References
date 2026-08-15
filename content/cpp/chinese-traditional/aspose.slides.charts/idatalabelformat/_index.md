---
title: IDataLabelFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示 DataLabel 的格式選項。
type: docs
weight: 963
url: /zh-hant/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat 類別

表示 [DataLabel](../datalabel/) 的格式選項。

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | 傳回圖表。唯讀 [IChart](../ichart/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | 表示資料標籤的格式。唯讀 [IFormat](../iformat/)。 |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | 讀取 **bool**。 |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | 表示 DataLabels 物件的格式字串。讀取 [System::String](../../system/string/)。 |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | 表示資料標籤的位置。讀取 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | 設定或傳回表示圖表上資料標籤分隔符的 Variant。讀取 [System::String](../../system/string/)。 |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | 表示指定圖表的資料標籤氣泡大小值顯示行為。True 表示顯示氣泡大小值，False 表示隱藏。讀取 **bool**。 |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | 表示指定圖表的資料標籤類別名稱顯示行為。True 表示在圖表的資料標籤上顯示類別名稱，False 表示隱藏。讀取 **bool**。 |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | 決定指定圖表的資料標籤將顯示為資料呼叫或資料標籤本身。 |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | 表示指定圖表的資料標籤儲存格值顯示行為。True 表示顯示儲存格值，False 表示隱藏。讀取 **bool**。 |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | 表示指定圖表的資料標籤引導線顯示行為。True 表示顯示引導線，False 表示隱藏。讀取 **bool**。 |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | 表示指定圖表的資料標籤圖例鍵顯示行為。True 表示圖例鍵可見。讀取 **bool**。 |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | 表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值，False 表示隱藏。讀取 **bool**。 |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | 傳回布林值以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱，False 表示隱藏。讀取 **bool**。 |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | 表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值，False 表示隱藏。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | 傳回圖表文字格式。唯讀 [IChartTextFormat](../icharttextformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件，並允許子類別以拷貝方式建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別以拷貝方式建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | 寫入 **bool**。 |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | 表示 DataLabels 物件的格式字串。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | 表示資料標籤的位置。寫入 [LegendDataLabelPosition](../legenddatalabelposition/)。 |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | 設定或傳回表示圖表上資料標籤分隔符的 Variant。寫入 [System::String](../../system/string/)。 |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | 表示指定圖表的資料標籤氣泡大小值顯示行為。True 表示顯示氣泡大小值，False 表示隱藏。寫入 **bool**。 |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | 表示指定圖表的資料標籤類別名稱顯示行為。True 表示顯示類別名稱，False 表示隱藏。寫入 **bool**。 |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | 決定指定圖表的資料標籤將顯示為資料呼叫或資料標籤本身。 |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | 表示指定圖表的資料標籤儲存格值顯示行為。True 表示顯示儲存格值，False 表示隱藏。寫入 **bool**。 |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | 表示指定圖表的資料標籤引導線顯示行為。True 表示顯示引導線，False 表示隱藏。寫入 **bool**。 |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | 表示指定圖表的資料標籤圖例鍵顯示行為。True 表示圖例鍵可見。寫入 **bool**。 |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | 表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值，False 表示隱藏。寫入 **bool**。 |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | 設定布林值以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱，False 表示隱藏。寫入 **bool**。 |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | 表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值，False 表示隱藏。寫入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 另請參閱

* 類別 [IFormattedTextContainer](../iformattedtextcontainer/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)