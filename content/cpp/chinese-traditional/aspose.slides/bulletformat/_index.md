---
title: BulletFormat
second_title: Aspose.Slides C++ API 參考
description: 表示段落項目符號格式化屬性。
type: docs
weight: 248
url: /zh-hant/aspose.slides/bulletformat/
---
## BulletFormat 類別


Represents paragraph bullet formatting properties.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | 設定當啟用項目符號時（如 PowerPoint 在啟用段落項目符號/編號時的行為），對有效段落的 Indent 與 MarginLeft 設定預設的非零位移。若項目符號被停用，則僅重設段落的 Indent 與 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的行為）。位移依目前的 bullet 上下文 - IBulletFormat::get(set)_Type、.NumberedBulletStyle 以及第一段的 FontHeight - 來套用。非零的位移會套用到目前段落的有效 Indent 與 MarginLeft（使結果值為區域值）。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 式的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 式的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| char16_t [get_Char](./get_char/)() override | 返回未繼承的段落的項目符號字元。讀取 **wchar_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | 返回未繼承的段落項目符號的顏色格式。唯讀 [IColorFormat](../icolorformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | 返回未繼承的段落項目符號的字型。讀取 [IFontData](../ifontdata/)。 |
| **float** [get_Height](./get_height/)() override | 返回未繼承的段落項目符號的高度。值 std::numeric_limits<float>::quiet_NaN() 表示項目符號繼承段落中第一段的高度。讀取 **float**。 |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | 判斷項目符號是否擁有自己的顏色或繼承自段落中的第一段。若項目符號有自己的顏色則 **[NullableBool::True](../nullablebool/)**，若繼承自第一段則 **[NullableBool::False](../nullablebool/)**。讀取 [NullableBool](../nullablebool/)。 |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | 判斷項目符號是否擁有自己的字型或繼承自段落中的第一段。若項目符號有自己的字型則 **[NullableBool::True](../nullablebool/)**，若繼承自第一段則 **[NullableBool::False](../nullablebool/)**。讀取 [NullableBool](../nullablebool/)。 |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | 返回未繼承的編號項目符號群組使用的第一個號碼。讀取 **int16_t**。 |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | 返回未繼承的編號項目符號的樣式。讀取 [Slides::NumberedBulletStyle](../numberedbulletstyle/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 返回未繼承的段落中用作項目符號的圖片。唯讀 [ISlidesPicture](../islidespicture/)。 |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | 返回未繼承的段落項目符號類型。讀取 [BulletType](../bullettype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承後的有效項目符號格式化資料。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於 string 與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Char](./set_char/)(char16_t) override | 設定未繼承的段落項目符號字元。寫入 **wchar_t**。 |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定未繼承的段落項目符號字型。寫入 [IFontData](../ifontdata/)。 |
| void [set_Height](./set_height/)(**float**) override | 設定未繼承的段落項目符號高度。值 std::numeric_limits<float>::quiet_NaN() 表示項目符號繼承段落中第一段的高度。寫入 **float**。 |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | 判斷項目符號是否有自己的顏色或繼承自段落中的第一段。若有自己的顏色則 **[NullableBool::True](../nullablebool/)**，若繼承則 **[NullableBool::False](../nullablebool/)**。寫入 [NullableBool](../nullablebool/)。 |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | 判斷項目符號是否有自己的字型或繼承自段落中的第一段。若有自己的字型則 **[NullableBool::True](../nullablebool/)**，若繼承則 **[NullableBool::False](../nullablebool/)**。寫入 [NullableBool](../nullablebool/)。 |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | 設定未繼承的編號項目符號群組使用的第一個號碼。寫入 **int16_t**。 |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | 設定未繼承的編號項目符號樣式。寫入 [Slides::NumberedBulletStyle](../numberedbulletstyle/)。 |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | 設定未繼承的段落項目符號類型。寫入 [BulletType](../bullettype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [PVIObject](../pviobject/)
* 類別 [IBulletFormat](../ibulletformat/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)