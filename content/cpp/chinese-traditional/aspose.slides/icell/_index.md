---
title: ICell
second_title: Aspose.Slides for C++ API 參考
description: 表示表格中的儲存格。
type: docs
weight: 1639
url: /zh-hant/aspose.slides/icell/
---
## ICell 類別


表示表格中的儲存格。

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | 判斷文字方塊是否在儲存格內居中。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | 傳回包含此儲存格格式屬性的 [CellFormat](../cellformat/) 物件。唯讀 [ICellFormat](../icellformat/)。 |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | 傳回父表格之表格格線中，當前儲存格所跨越的欄位數量。此屬性允許儲存格呈現合併的外觀，因為它跨越表格中其他儲存格的垂直邊界。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | 取得儲存格的第一欄。唯讀 [IColumn](../icolumn/)。 |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | 傳回儲存格所覆蓋之第一欄的索引。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | 取得儲存格的第一列。唯讀 [IRow](../irow/)。 |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | 傳回儲存格所覆蓋之第一列的索引。唯讀 **int32_t**。 |
| virtual **double** [get_Height](./get_height/)() | 傳回儲存格的高度。唯讀 **double**。 |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | 若儲存格與任何已調整的儲存格合併則傳回 true，否則傳回 false。唯讀 **bool**。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | 傳回 [TextFrame](../textframe/) 中的底部邊距。讀取 **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | 傳回 [TextFrame](../textframe/) 中的左側邊距。讀取 **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | 傳回 [TextFrame](../textframe/) 中的右側邊距。讀取 **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | 傳回 [TextFrame](../textframe/) 中的頂部邊距。讀取 **double**。 |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | 傳回儲存格的最小高度。這是所有儲存格所跨越之列的最小高度之總和。唯讀 **double**。 |
| virtual **double** [get_OffsetX](./get_offsetx/)() | 傳回表格左側至儲存格左側的距離。唯讀 **double**。 |
| virtual **double** [get_OffsetY](./get_offsety/)() | 傳回表格頂部至儲存格頂部的距離。唯讀 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 傳回簡報。唯讀 [IPresentation](../ipresentation/)。 |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | 傳回合併儲存格跨越的列數。此屬性與其他儲存格的 vMerge 屬性結合使用，以指定水平合併的起始儲存格。唯讀 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 傳回基礎投影片。唯讀 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | 傳回儲存格的父級 [Table](../table/) 物件。唯讀 [ITable](../itable/)。 |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | 傳回文字錨點類型。讀取 [Slides::TextAnchorType](../textanchortype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | 傳回儲存格的文字框。唯讀 [ITextFrame](../itextframe/)。 |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 傳回垂直文字的類型。讀取 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual **double** [get_Width](./get_width/)() | 傳回儲存格的寬度。唯讀 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似功能。允許自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似功能。允許自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況的特化版本。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況的特化版本。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數下降指定的數值。 |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | 判斷文字方塊是否在儲存格內居中。寫入 **bool**。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | 設定 [TextFrame](../textframe/) 中的底部邊距。寫入 **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | 設定 [TextFrame](../textframe/) 中的左側邊距。寫入 **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | 設定 [TextFrame](../textframe/) 中的右側邊距。寫入 **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | 設定 [TextFrame](../textframe/) 中的頂部邊距。寫入 **double**。 |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | 設定文字錨點類型。寫入 [Slides::TextAnchorType](../textanchortype/)。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | 設定垂直文字的類型。寫入 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板引數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | 依欄位索引將儲存格分割為兩個儲存格。 |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | 依高度分割儲存格。 |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | 依列索引將儲存格分割為兩個儲存格。 |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | 依寬度分割儲存格。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類似功能。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [ISlideComponent](../islidecomponent/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)