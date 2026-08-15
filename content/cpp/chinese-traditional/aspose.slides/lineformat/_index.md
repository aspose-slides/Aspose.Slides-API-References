---
title: LineFormat
second_title: Aspose.Slides for C++ API 參考文件
description: 表示線條的格式。
type: docs
weight: 4382
url: /zh-hant/aspose.slides/lineformat/
---
## LineFormat 類別

表示線條的格式。

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | 判斷兩個 [LineFormat](./) 實例是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | 傳回線條對齊方式。請參閱 [LineAlignment](../linealignment/)。 |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | 傳回線條起始端的箭頭長度。請參閱 [LineArrowheadLength](../linearrowheadlength/)。 |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | 傳回線條起始端的箭頭樣式。請參閱 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | 傳回線條起始端的箭頭寬度。請參閱 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | 傳回線條端點樣式。請參閱 [LineCapStyle](../linecapstyle/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | 傳回自訂虛線圖樣。請參閱 **float**[]. |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | 傳回線條虛線樣式。請參閱 [LineDashStyle](../linedashstyle/)。 |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | 傳回線條結尾端的箭頭長度。請參閱 [LineArrowheadLength](../linearrowheadlength/)。 |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | 傳回線條結尾端的箭頭樣式。請參閱 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | 傳回線條結尾端的箭頭寬度。請參閱 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | 傳回線條的填充格式。唯讀 [ILineFillFormat](../ilinefillformat/)。 |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | 若線條格式未定義（剛建立、預設），傳回 true。唯讀 **bool**。 |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | 傳回線條的連接樣式。請參閱 [LineJoinStyle](../linejoinstyle/)。 |
| **float** [get_MiterLimit](./get_miterlimit/)() override | 傳回線條的斜角限制。請參閱 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 傳回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 傳回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | 傳回線條的草圖格式。唯讀 [ILineFillFormat](../ilinefillformat/)。 |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | 傳回線條樣式。請參閱 [LineStyle](../linestyle/)。 |
| **double** [get_Width](./get_width/)() override | 傳回線條的寬度。請參閱 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承後的有效線條格式資料。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 傳回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的型別實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允許自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | 設定線條對齊方式。寫入 [LineAlignment](../linealignment/)。 |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | 設定線條起始端的箭頭長度。寫入 [LineArrowheadLength](../linearrowheadlength/)。 |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | 設定線條起始端的箭頭樣式。寫入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | 設定線條起始端的箭頭寬度。寫入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | 設定線條端點樣式。寫入 [LineCapStyle](../linecapstyle/)。 |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | 設定自訂虛線圖樣。寫入 **float**[]。 |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | 設定線條虛線樣式。寫入 [LineDashStyle](../linedashstyle/)。 |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | 設定線條結尾端的箭頭長度。寫入 [LineArrowheadLength](../linearrowheadlength/)。 |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | 設定線條結尾端的箭頭樣式。寫入 [LineArrowheadStyle](../linearrowheadstyle/)。 |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | 設定線條結尾端的箭頭寬度。寫入 [LineArrowheadWidth](../linearrowheadwidth/)。 |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | 設定線條連接樣式。寫入 [LineJoinStyle](../linejoinstyle/)。 |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | 設定線條的斜角限制。寫入 **float**。 |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | 設定線條樣式。寫入 [LineStyle](../linestyle/)。 |
| void [set_Width](./set_width/)(**double**) override | 設定線條寬度。寫入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 運算式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [PVIObject](../pviobject/)
* 類別 [ILineFormat](../ilineformat/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)