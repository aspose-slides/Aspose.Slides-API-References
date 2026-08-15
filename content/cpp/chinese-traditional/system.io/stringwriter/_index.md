---
title: StringWriter
second_title: Aspose.Slides for C++ API 參考
description: "實作一個將資訊寫入字串的 TextWriter。此類別的物件應僅使用 System::MakeObject() 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 417
url: /zh-hant/system.io/stringwriter/
---
## StringWriter 類別

Implements a [TextWriter](../textwriter/) that writes information to a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## 方法

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | 關閉串流並釋放取得的資源。 |
| void [Dispose](../textwriter/dispose/)() override | 釋放目前物件使用的所有資源並關閉底層串流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual void [Flush](../textwriter/flush/)() | 將緩衝區的內容刷新至底層串流。 |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | 回傳目前使用的編碼。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | 回傳目前使用的 [IFormatProvider](../../system/iformatprovider/) 物件。 |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | 回傳目前使用的 [IFormatProvider](../../system/iformatprovider/) 物件。 |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | 回傳行終止字串。 |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | 回傳行終止字串。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | 回傳目前使用的 StringBuilder。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | 設定行終止字串。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 使用指定的 StringBuilder 與 [IFormatProvider](../../system/iformatprovider/) 建構 [StringWriter](./) 的新實例。 |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 使用指定的 StringBuilder 與來自目前文化的 [IFormatProvider](../../system/iformatprovider/) 建構 [StringWriter](./) 的新實例。 |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | 使用指定的 [IFormatProvider](../../system/iformatprovider/) 建構 [StringWriter](./) 的新實例。 |
|  [StringWriter](./stringwriter/)() | 使用來自目前文化的 [IFormatProvider](../../system/iformatprovider/) 建構 [StringWriter](./) 的新實例。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 回傳底層字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Write](./write/)(char_t) override | 將指定的字符寫入串流。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 將指定字元陣列中指定的子範圍寫入串流。 |
| void [Write](./write/)(const [String](../../system/string/)\&) override | 將指定字串寫入串流。 |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 將指定物件的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**bool**) | 將指定布林值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | 將指定 [Decimal](../../system/decimal/) 物件的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**double**) | 將指定雙精度浮點值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(int) | 將指定 32 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**int64_t**) | 將指定 64 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**float**) | 將指定單精度浮點值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | 將指定無號 32 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | 將指定無號 64 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 將指定陣列中的所有字符寫入串流。 |
| virtual void [Write](../textwriter/write/)(const char_t *) | 將指定的 C 字串寫入串流。 |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | 將指定 [TypeInfo](../../system/typeinfo/) 物件的字串表示寫入串流。 |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | 將指定值依照指定格式寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)() | 將行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 將指定物件的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | 將指定布林值的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | 將指定字符加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | 將指定 [Decimal](../../system/decimal/) 物件的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | 將指定雙精度浮點值的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(int) | 將指定 32 位元整數值的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | 將指定 64 位元整數值的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | 將指定單精度浮點值的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | 將指定字串加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | 將指定無號 32 位元整數值的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | 將指定無號 64 位元整數值的字串表示加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 將指定陣列中的所有字符加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 將指定字元陣列中指定的 UTF-16 子區間加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | 將指定的 C 字串加上行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 將指定 [TypeInfo](../../system/typeinfo/) 物件的字串表示加上行終止字元寫入串流。 |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 將指定值依照指定格式寫入串流，並附加行終止字元。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | 解構函式。 |

## 參見

* 類別 [TextWriter](../textwriter/)
* 命名空間 [System::IO](../)
* 程式庫 [Aspose.Slides](../../)