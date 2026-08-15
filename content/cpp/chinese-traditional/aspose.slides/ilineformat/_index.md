---
title: ILineFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示線條的格式。
type: docs
weight: 2757
url: /zh-hant/aspose.slides/ilineformat/
---
## ILineFormat 類別


表示線條的格式。

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | 判斷兩個 [LineFormat](../lineformat/) 實例是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，當兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | 傳回線條對齊方式。讀取 [LineAlignment](../linealignment/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | 傳回線條起始端的箭頭長度。讀取 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | 傳回線條起始端的箭頭樣式。讀取 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | 傳回線條起始端的箭頭寬度。讀取 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | 傳回線條端帽樣式。讀取 [LineCapStyle](../linecapstyle/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | 傳回自訂虛線模式。讀取 **float**[]。 |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | 傳回線條虛線樣式。讀取 [LineDashStyle](../linedashstyle/)。 |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | 傳回線條結尾端的箭頭長度。讀取 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | 傳回線條結尾端的箭頭樣式。讀取 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | 傳回線條結尾端的箭頭寬度。讀取 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | 傳回線條的填滿格式。唯讀 [ILineFillFormat](../ilinefillformat/)。 |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | 如果線條格式未定義（剛建立，預設），則傳回 true。唯讀 **bool**。 |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | 傳回線條連接樣式。讀取 [LineJoinStyle](../linejoinstyle/)。 |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | 傳回線條斜接限制。讀取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | 傳回線條的草圖格式。唯讀 [ISketchFormat](../isketchformat/)。 |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | 傳回線條樣式。讀取 [LineStyle](../linestyle/)。 |
| virtual **double** [get_Width](./get_width/)() | 傳回線條寬度。讀取 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | 取得套用繼承後的有效線條格式資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 防護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | 設定線條對齊方式。寫入 [LineAlignment](../linealignment/)。 |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | 設定線條起始端的箭頭長度。寫入 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | 設定線條起始端的箭頭樣式。寫入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | 設定線條起始端的箭頭寬度。寫入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | 設定線條端帽樣式。寫入 [LineCapStyle](../linecapstyle/)。 |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | 設定自訂虛線模式。寫入 **float**[]。 |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | 設定線條虛線樣式。寫入 [LineDashStyle](../linedashstyle/)。 |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | 設定線條結尾端的箭頭長度。寫入 [LineArrowheadLength](../linearrowheadlength/)。 |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | 設定線條結尾端的箭頭樣式。寫入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | 設定線條結尾端的箭頭寬度。寫入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | 設定線條連接樣式。寫入 [LineJoinStyle](../linejoinstyle/)。 |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | 設定線條斜接限制。寫入 **float**。 |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | 設定線條樣式。寫入 [LineStyle](../linestyle/)。 |
| virtual void [set_Width](./set_width/)(**double**) | 設定線條寬度。寫入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 防護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [ILineParamSource](../ilineparamsource/)
* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)