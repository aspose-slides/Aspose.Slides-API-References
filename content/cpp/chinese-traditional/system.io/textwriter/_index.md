---
title: TextWriter
second_title: Aspose.Slides for C++ API 參考
description: "此為表示將字元序列寫入不同目的地之寫入器之基礎類別。此類別的物件應僅透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 System::SmartPtr 指標，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 443
url: /zh-hant/system.io/textwriter/
---
## TextWriter 類別


一個用於表示將字元序列寫入不同目的地的寫入器的基礎類別。此類別的物件應僅透過 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
class TextWriter : public System::IDisposable
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual void [Close](./close/)() | 關閉串流並釋放取得的資源。 |
| void [Dispose](./dispose/)() override | 釋放目前物件使用的所有資源並關閉底層串流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual void [Flush](./flush/)() | 將緩衝區內容刷新到底層串流。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 回傳目前使用的編碼。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | 回傳目前使用的 [IFormatProvider](../../system/iformatprovider/) 物件。 |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | 回傳目前使用的 [IFormatProvider](../../system/iformatprovider/) 物件。 |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | 回傳換行字元字串。 |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | 回傳換行字元字串。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。提供自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。提供自訂型別的複製功能。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特殊化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特殊化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | 設定換行字元字串。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共享參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。提供將自訂物件轉換為字串的功能。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 將指定物件的字串表示寫入串流。 |
| virtual void [Write](./write/)(**bool**) | 將指定布林值的字串表示寫入串流。 |
| virtual void [Write](./write/)(char_t) | 將指定字元寫入串流。 |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | 將指定 [Decimal](../../system/decimal/) 物件的字串表示寫入串流。 |
| virtual void [Write](./write/)(**double**) | 將指定雙精度浮點值的字串表示寫入串流。 |
| virtual void [Write](./write/)(int) | 將指定 32 位元整數值的字串表示寫入串流。 |
| virtual void [Write](./write/)(**int64_t**) | 將指定 64 位元整數值的字串表示寫入串流。 |
| virtual void [Write](./write/)(**float**) | 將指定單精度浮點值的字串表示寫入串流。 |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | 將指定字串寫入串流。 |
| virtual void [Write](./write/)(**uint32_t**) | 將指定無號 32 位元整數值的字串表示寫入串流。 |
| virtual void [Write](./write/)(**uint64_t**) | 將指定無號 64 位元整數值的字串表示寫入串流。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 將指定陣列中的所有字元寫入串流。 |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 將指定字元陣列中指定的 UTF-16 子區段寫入串流。 |
| virtual void [Write](./write/)(const char_t *) | 將指定的 C 字串寫入串流。 |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | 將指定 [TypeInfo](../../system/typeinfo/) 物件的字串表示寫入串流。 |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | 將指定的值依照指定格式寫入串流。 |
| virtual void [WriteLine](./writeline/)() | 將換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 將指定物件的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(**bool**) | 將指定布林值的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(char_t) | 將指定字元及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | 將指定 [Decimal](../../system/decimal/) 物件的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(**double**) | 將指定雙精度浮點值的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(int) | 將指定 32 位元整數值的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(**int64_t**) | 將指定 64 位元整數值的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(**float**) | 將指定單精度浮點值的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | 將指定字串及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | 將指定無號 32 位元整數值的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | 將指定無號 64 位元整數值的字串表示及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 將指定陣列中的所有字元及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 將指定字元陣列中指定的 UTF-16 子區段及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(const char_t *) | 將指定的 C 字串及其後的換行字元寫入串流。 |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 將指定 [TypeInfo](../../system/typeinfo/) 物件的字串表示及其後的換行字元寫入串流。 |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 將指定的值依照指定格式及其後的換行字元寫入串流。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
| virtual  [~TextWriter](./~textwriter/)() | 解構函式。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別的共享指標別名。 |

## 參見

* 類別 [IDisposable](../../system/idisposable/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)