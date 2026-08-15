---
title: NumberFormatInfo
second_title: Aspose.Slides for C++ API 參考文件
description: "保存有關如何格式化數字的資訊。只有在非唯讀物件上才會啟用設定子操作。此類別的物件應僅使用 System::MakeObject() 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用此指標將其作為參數傳遞給函式。"
type: docs
weight: 248
url: /zh-hant/system.globalization/numberformatinfo/
---
## NumberFormatInfo 類別

保存有關如何格式化數字的資訊。只有在非唯讀物件上才會啟用設定子操作。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式來配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | 複製格式資訊。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | 取得貨幣小數位的數量。 |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | 取得貨幣小數分隔符號。 |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | 取得貨幣千位分組分隔符號。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | 取得每組的貨幣小數位數。 |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | 取得貨幣負號格式。 |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | 取得貨幣正號格式。 |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | 取得貨幣符號。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | 取得目前執行緒文化定義的數字格式資訊。 |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | 取得指定數字形狀顯示方式的值。 |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | 取得不變文化定義的數字格式資訊。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | 檢查格式是否為唯讀。 |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | 取得非數值 (NaN) 符號。 |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | 取得數字符號 (0 到 9)。 |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | 取得負無限大符號。 |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | 取得負號。 |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | 取得小數位數。 |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | 取得小數分隔符號。 |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | 取得數字千位分組分隔符號。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | 取得每組的位數。 |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | 取得數字負號格式。 |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | 取得百分比值的小數位數。 |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | 取得百分比值的小數分隔符號。 |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | 取得百分比值的千位分組分隔符號。 |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | 取得每個百分比值群組的位數。 |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | 取得百分比負號格式。 |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | 取得百分比正號格式。 |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | 取得百分比符號。 |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | 取得千分比符號。 |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | 取得正無限大符號。 |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | 取得正號。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | 取得特定類型的格式化程式。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 取得與格式提供者相關聯的格式化程式。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述之類型的實例。相當於 C# 'is' 運算子。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [NumberFormatInfo](./numberformatinfo/)() | 預設建構子（不變 [NumberFormatInfo](./)）。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | 取得只讀版本的格式化程式。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | 設定貨幣小數位的數量。 |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | 設定貨幣小數分隔符號。 |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | 設定貨幣千位分組分隔符號。 |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 設定每組的貨幣小數位數。 |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | 設定貨幣負號格式。 |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | 設定貨幣正號格式。 |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | 設定貨幣符號。 |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | 設定指定數字形狀顯示方式的值。 |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | 設定非數值 (NaN) 符號。 |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 設定數字符號 (0 到 9)。 |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | 設定負無限大符號。 |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | 設定負號。 |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | 設定小數位數。 |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | 設定小數分隔符號。 |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | 設定數字千位分組分隔符號。 |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 設定每組的位數。 |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | 設定數字負號格式。 |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | 設定百分比值的小數位數。 |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | 設定百分比值的小數分隔符號。 |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | 設定百分比值的千位分組分隔符號。 |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | 設定每個百分比值群組的位數。 |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | 設定百分比負號格式。 |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | 設定百分比正號格式。 |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | 設定百分比符號。 |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | 設定千分比符號。 |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | 設定正無限大符號。 |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | 設定正號。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享指標）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [Object](../../system/object/)
* 類別 [IFormatProvider](../../system/iformatprovider/)
* 類別 [ICloneable](../../system/icloneable/)
* 命名空間 [System::Globalization](../)
* 函式庫 [Aspose.Slides](../../)