---
title: Cell
second_title: Aspose.Slides for C++ API 參考
description: 代表表格中的儲存格。
type: docs
weight: 300
url: /zh-hant/aspose.slides/cell/
---
## Cell 類別

代表表格中的一個儲存格。

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | 判斷文字方塊是否置中於儲存格內。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | 傳回包含此儲存格格式屬性的 [CellFormat](../cellformat/) 物件。唯讀 [ICellFormat](../icellformat/)。 |
| **int32_t** [get_ColSpan](./get_colspan/)() override | 傳回父表格的表格格線中當前儲存格應跨越的欄位數量。此屬性允許儲存格呈現合併的外觀，因為它們跨越表格中其他儲存格的垂直邊界。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | 取得儲存格的第一欄。唯讀 [IColumn](../icolumn/)。 |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | 傳回儲存格所覆蓋的第一欄索引。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | 取得儲存格的第一列。唯讀 [IRow](../irow/)。 |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | 傳回儲存格所覆蓋的第一列索引。唯讀 **int32_t**。 |
| **double** [get_Height](./get_height/)() override | 傳回儲存格的高度。唯讀 **double**。 |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | 若儲存格與任何已調整的儲存格合併則傳回 true，否則傳回 false。唯讀 **bool**。 |
| **double** [get_MarginBottom](./get_marginbottom/)() override | 傳回 [TextFrame](../textframe/) 中的底部邊距。讀取 **double**。 |
| **double** [get_MarginLeft](./get_marginleft/)() override | 傳回 [TextFrame](../textframe/) 中的左側邊距。讀取 **double**。 |
| **double** [get_MarginRight](./get_marginright/)() override | 傳回 [TextFrame](../textframe/) 中的右側邊距。讀取 **double**。 |
| **double** [get_MarginTop](./get_margintop/)() override | 傳回 [TextFrame](../textframe/) 中的上側邊距。讀取 **double**。 |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | 傳回儲存格的最小高度。這是儲存格所覆蓋的所有列的最小高度之和。唯讀 **double**。 |
| **double** [get_OffsetX](./get_offsetx/)() override | 傳回表格左側到儲存格左側的距離。唯讀 **double**。 |
| **double** [get_OffsetY](./get_offsety/)() override | 傳回表格上側到儲存格上側的距離。唯讀 **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | 傳回儲存格的父簡報。唯讀 [IPresentation](../ipresentation/)。 |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | 傳回合併儲存格跨越的列數。此屬性與其他儲存格的 vMerge 屬性結合使用，以指定水平合併的起始儲存格。唯讀 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | 傳回儲存格的父投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | 傳回儲存格的父 [Table](../table/) 物件。唯讀 [ITable](../itable/)。 |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | 傳回文字錨點類型。讀取 [Slides::TextAnchorType](../textanchortype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | 傳回儲存格的文字框。唯讀 [ITextFrame](../itextframe/)。 |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | 傳回垂直文字的類型。讀取 [Slides::TextVerticalType](../textverticaltype/)。 |
| **double** [get_Width](./get_width/)() override | 傳回儲存格的寬度。唯讀 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | 判斷文字方塊是否置中於儲存格內。寫入 **bool**。 |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | 設定 [TextFrame](../textframe/) 中的底部邊距。寫入 **double**。 |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | 設定 [TextFrame](../textframe/) 中的左側邊距。寫入 **double**。 |
| void [set_MarginRight](./set_marginright/)(**double**) override | 設定 [TextFrame](../textframe/) 中的右側邊距。寫入 **double**。 |
| void [set_MarginTop](./set_margintop/)(**double**) override | 設定 [TextFrame](../textframe/) 中的上側邊距。寫入 **double**。 |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | 設定文字錨點類型。寫入 [Slides::TextAnchorType](../textanchortype/)。 |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | 設定垂直文字類型。寫入 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | 依欄位索引將儲存格分割為兩個儲存格。 |
| void [SplitByHeight](./splitbyheight/)(**double**) override | 依高度分割儲存格。 |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | 依列索引將儲存格分割為兩個儲存格。 |
| void [SplitByWidth](./splitbywidth/)(**double**) override | 依寬度分割儲存格。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [IDOMObject](../idomobject/)
* 類別 [ICell](../icell/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)