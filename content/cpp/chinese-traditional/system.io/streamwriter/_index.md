---
title: StreamWriter
second_title: Aspose.Slides for C++ API 參考
description: "表示一個將字元寫入位元組串流的寫入器。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用此指標將其作為參數傳遞給函式。"
type: docs
weight: 391
url: /zh-hant/system.io/streamwriter/
---
## StreamWriter 類別

表示一個將字元寫入位元組串流的寫入器。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

```cpp
class StreamWriter : public System::IO::TextWriter
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [Close](./close/)() override | 關閉串流並釋放取得的資源。 |
| void [Dispose](./dispose/)() override | 釋放目前物件使用的所有資源並關閉底層串流。 |
| virtual void [Dispose](./dispose/)(**bool**) | 釋放目前物件使用的所有資源並關閉底層串流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [Flush](./flush/)() override | 將緩衝區內容刷新至底層串流，然後刷新底層串流。 |
| **bool** [get_AutoFlush](./get_autoflush/)() const | 傳回一個值，指示 [StreamWriter](./) 是否會在每次呼叫方法 [StreamWriter::Write](./write/) 時將資料刷新至底層串流。 |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | 傳回指向代表底層串流之物件的共享指標。 |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | 傳回目前使用的編碼。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | 傳回目前使用的 [IFormatProvider](../../system/iformatprovider/) 物件。 |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | 傳回目前使用的 [IFormatProvider](../../system/iformatprovider/) 物件。 |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | 傳回行終止字串。 |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | 傳回行終止字串。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | 傳回一個值，指定每次呼叫方法 [StreamWriter::Write](./write/) 時 [StreamWriter](./) 是否應將資料刷新至底層串流。 |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | 設定行終止字串。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 建立 [StreamWriter](./) 物件的實例，使用 UTF-8 編碼將字元寫入指定的底層串流，並使用預設大小為 1024 位元組的緩衝區。 |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 建立 [StreamWriter](./) 物件的實例，使用指定的編碼將字元寫入指定的底層串流，並使用預設大小為 1024 位元組的緩衝區。 |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | 建立 [StreamWriter](./) 物件的實例，使用指定的編碼將字元寫入指定的底層串流，並使用指定大小的緩衝區。參數指定在 [StreamWriter](./) 物件釋放時是否應關閉底層串流。 |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | 建立 [StreamWriter](./) 物件的實例，使用 UTF-8 編碼將字元寫入指定的檔案，並使用預設大小為 1024 位元組的緩衝區。 |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | 建立 [StreamWriter](./) 物件的實例，使用指定的編碼將字元寫入指定的檔案，並使用預設大小為 1024 位元組的緩衝區。參數指定資料是應附加至檔案還是覆寫檔案。 |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | 建立 [StreamWriter](./) 物件的實例，使用指定的編碼與緩衝區大小將字元寫入指定的檔案。參數指定資料是應附加至檔案還是覆寫檔案。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Write](./write/)(char_t) override | 將指定字元寫入串流。 |
| void [Write](./write/)(const [String](../../system/string/)\&) override | 將指定字串寫入串流。 |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | 將指定物件的字串表示寫入串流。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | 將指定陣列中的所有字元寫入串流。 |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 將指定字元陣列中指定範圍的 UTF-16 字元寫入串流。 |
| void [Write](./write/)(const char_t *) override | 將指定的 C 字串寫入串流。 |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | 將指定物件的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**bool**) | 將指定布林值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | 將指定 [Decimal](../../system/decimal/) 物件的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**double**) | 將指定雙精度浮點值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(int) | 將指定 32 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**int64_t**) | 將指定 64 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**float**) | 將指定單精度浮點值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | 將指定無號 32 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | 將指定無號 64 位元整數值的字串表示寫入串流。 |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | 將指定 [TypeInfo](../../system/typeinfo/) 物件的字串表示寫入串流。 |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | 按指定格式將指定值寫入串流。 |
| void [WriteLine](./writeline/)() override | 將行終止字元寫入串流。 |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | 將指定字串與行終止字元寫入串流。 |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | 將指定物件的字串表示與行終止字元寫入串流。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | 將指定陣列中的所有字元與行終止字元寫入串流。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 將指定字元陣列中指定範圍的 UTF-16 字元與行終止字元寫入串流。 |
| void [WriteLine](./writeline/)(const char_t *) override | 將指定的 C 字串與行終止字元寫入串流。 |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | 將指定物件的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | 將指定布林值的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | 將指定字元與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | 將指定 [Decimal](../../system/decimal/) 物件的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | 將指定雙精度浮點值的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(int) | 將指定 32 位元整數值的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | 將指定 64 位元整數值的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | 將指定單精度浮點值的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | 將指定無號 32 位元整數值的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | 將指定無號 64 位元整數值的字串表示與行終止字元寫入串流。 |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | 將指定 [TypeInfo](../../system/typeinfo/) 物件的字串表示與行終止字元寫入串流。 |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | 按指定格式將指定值寫入串流，並加上行終止字元。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
|  [~StreamWriter](./~streamwriter/)() | 解構函式。 |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | 解構函式。 |

## 另請參閱

* 類別 [TextWriter](../textwriter/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)