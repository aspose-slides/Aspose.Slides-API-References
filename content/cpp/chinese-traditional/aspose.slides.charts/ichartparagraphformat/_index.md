---
title: IChartParagraphFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示圖表的段落格式屬性。
type: docs
weight: 781
url: /zh-hant/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat 類別

表示圖表的段落格式屬性。

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | 回傳段落中的文字對齊方式。請參閱 [TextAlignment](../../aspose.slides/textalignment/)。 |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | 回傳預設的製表位大小。請參閱 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | 判斷段落中是否使用東亞換行。請參閱 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | 回傳段落中的字型對齊方式。請參閱 [Slides::FontAlignment](../../aspose.slides/fontalignment/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | 判斷段落中是否使用懸掛標點。請參閱 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_Indent](./get_indent/)() | 回傳段落的首行縮排/懸掛縮排。懸掛縮排可使用負值定義。請參閱 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | 判斷段落中是否使用拉丁換行。請參閱 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | 回傳段落左側邊距。請參閱 **float**。 |
| virtual **float** [get_MarginRight](./get_marginright/)() | 回傳段落右側邊距。請參閱 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | 判斷段落中是否使用從右至左書寫。請參閱 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | 回傳段落最後一行之後的空間量。請參閱 **float**。 |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | 回傳段落第一行之前的空間量。請參閱 **float**。 |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | 回傳段落基線之間的空間量。請參閱 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | 回傳指定索引處的段落製表位。唯讀 [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | 回傳段落的製表位。唯讀 [ITabCollection](../../aspose.slides/itabcollection/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型所描述的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的數值。 |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | 設定段落中的文字對齊方式。寫入 [TextAlignment](../../aspose.slides/textalignment/)。 |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | 設定預設的製表位大小。寫入 **float**。 |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷段落中是否使用東亞換行。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | 設定段落中的字型對齊方式。寫入 [Slides::FontAlignment](../../aspose.slides/fontalignment/)。 |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷段落中是否使用懸掛標點。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_Indent](./set_indent/)(**float**) | 設定段落的首行縮排/懸掛縮排。懸掛縮排可使用負值定義。寫入 **float**。 |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷段落中是否使用拉丁換行。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | 設定段落左側邊距。寫入 **float**。 |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | 設定段落右側邊距。寫入 **float**。 |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷段落中是否使用從右至左書寫。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | 設定段落最後一行之後的空間量。寫入 **float**。 |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | 設定段落第一行之前的空間量。寫入 **float**。 |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | 設定段落基線之間的空間量。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共用指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 構造式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)