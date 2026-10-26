---
title: IBulletFormat
second_title: Aspose.Slides for C++ API 參考
description: 代表段落項目符號格式化屬性。
type: docs
weight: 1561
url: /zh-hant/aspose.slides/ibulletformat/
---
## IBulletFormat 類別


表示段落項目符號格式化屬性。

```cpp
class IBulletFormat : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | 設定預設的非零位移，以在啟用項目符號時對有效段落的 Indent 與 MarginLeft 產生作用（如同 PowerPoint 在啟用段落項目符號/編號時的行為）。若項目符號被停用，則僅重設段落的 Indent 與 MarginLeft（如同 PowerPoint 在停用段落項目符號/編號時的行為）。位移會根據目前的項目符號環境套用——IBulletFormat::get(set)_Type、.NumberedBulletStyle 與第一段落部份的 FontHeight。非零位移會套用到目前段落的有效 Indent 與 MarginLeft（使結果值為局部值）。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參照類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual char16_t [get_Char](./get_char/)() | 取得段落項目符號字元，未繼承。讀取 **wchar_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | 取得段落項目符號的顏色格式，未繼承。唯讀 [IColorFormat](../icolorformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | 取得段落項目符號的字型，未繼承。讀取 [IFontData](../ifontdata/)。 |
| virtual **float** [get_Height](./get_height/)() | 取得段落項目符號的高度，未繼承。值 std::numeric_limits<float>::quiet_NaN() 表示項目符號從段落第一部份繼承高度。讀取 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | 判斷項目符號是否擁有自己的顏色或從段落第一部份繼承。**[NullableBool::True](../nullablebool/)** 表示項目符號有自己的顏色，**[NullableBool::False](../nullablebool/)** 表示項目符號從段落第一部份繼承顏色。讀取 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | 判斷項目符號是否擁有自己的字型或從段落第一部份繼承。**[NullableBool::True](../nullablebool/)** 表示項目符號有自己的字型，**[NullableBool::False](../nullablebool/)** 表示項目符號從段落第一部份繼承字型。讀取 [NullableBool](../nullablebool/)。 |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | 取得未繼承的編號項目符號群組使用的第一個編號。讀取 **int16_t**。 |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | 取得未繼承的編號項目符號樣式。讀取 [NumberedBulletStyle](../numberedbulletstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 取得未繼承的段落項目符號圖片。唯讀 [ISlidesPicture](../islidespicture/)。 |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | 取得未繼承的段落項目符號類型。讀取 [BulletType](../bullettype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參照計數資料結構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | 取得套用繼承後的有效項目符號格式資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 類似 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。類似 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。類似 C# `is` 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 類似 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何資料，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何資料，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定數值減少共享參照計數。 |
| virtual void [set_Char](./set_char/)(char16_t) | 設定段落項目符號字元，未繼承。寫入 **wchar_t**。 |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定段落項目符號字型，未繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_Height](./set_height/)(**float**) | 設定段落項目符號高度，未繼承。值 std::numeric_limits<float>::quiet_NaN() 表示項目符號從段落第一部份繼承高度。寫入 **float**。 |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | 判斷項目符號是否擁有自己的顏色或從段落第一部份繼承。**[NullableBool::True](../nullablebool/)** 表示項目符號有自己的顏色，**[NullableBool::False](../nullablebool/)** 表示項目符號從段落第一部份繼承顏色。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | 判斷項目符號是否擁有自己的字型或從段落第一部份繼承。**[NullableBool::True](../nullablebool/)** 表示項目符號有自己的字型，**[NullableBool::False](../nullablebool/)** 表示項目符號從段落第一部份繼承字型。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | 設定未繼承的編號項目符號群組使用的第一個編號。寫入 **int16_t**。 |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | 設定未繼承的編號項目符號樣式。寫入 [NumberedBulletStyle](../numberedbulletstyle/)。 |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | 設定段落項目符號類型，未繼承。寫入 [BulletType](../bullettype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共享參照計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並返回共享參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 類似 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參照計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)