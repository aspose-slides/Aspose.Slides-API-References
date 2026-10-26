---
title: ConsoleOutput
second_title: Aspose.Slides C++ API 參考
description: "表示標準輸出串流。此類別的物件應僅透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 209
url: /zh-hant/system/consoleoutput/
---
## ConsoleOutput 類別

表示標準輸出串流。此類別的物件應僅透過 [System::MakeObject()](../makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../smartptr/) 指標，並使用此指標作為參數傳遞給函式。

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | 關閉串流並釋放已取得的資源。 |
| void [Dispose](../../system.io/textwriter/dispose/)() override | 釋放目前物件使用的所有資源，並關閉底層串流。 |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | 使用 C# [Object.Equals](../object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const&, T2 const&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const&, T2 const&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../object/equals/)(**float** const&, **float** const&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../object/equals/)(**double** const&, **double** const&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase&, void **) const | 僅供內部使用。 |
| virtual void [Flush](../../system.io/textwriter/flush/)() | 將緩衝區內容刷新至底層串流。 |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | 始終回傳 ASCII 編碼。 |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | 回傳目前使用的 [IFormatProvider](../iformatprovider/) 物件。 |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | 回傳目前使用的 [IFormatProvider](../iformatprovider/) 物件。 |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | 回傳行終止字串。 |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | 回傳行終止字串。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../object/gettype/) 呼叫。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 檢查物件是否為 targetType 描述的型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../object/memberwiseclone/) 方法。啟用自訂型別的克隆功能。 |
|  [Object](../object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../object/object/)([Object](../object/) const&) | 副本建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const&, [ptr](../object/ptr/) const&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const&, T const&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) 的特化版，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const&, [String](../string/) const&) | [Object::ReferenceEquals](../object/referenceequals/) 的特化版，用於字串的情況。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | 設定行終止字串。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../string/) [ToString](../object/tostring/)() const | 相當於 C# [Object.ToString()](../object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | 實作 C# typeof([System.Object](../object/)) 結構。 |
| void [Unlock](../object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [Write](./write/)(**bool**) override | 將指定的 bool 值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 將指定物件的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(char_t) override | 將指定的字元值輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)([Decimal](../decimal/)) override | 將 [Decimal](../decimal/) 值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(**double**) override | 將雙精度浮點值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(**int32_t**) override | 將 32 位元整數值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(**int64_t**) override | 將 64 位元整數值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(**float**) override | 將單精度浮點值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(const [String](../string/)\&) override | 將指定的字串物件輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(**uint32_t**) override | 將無號 32 位元整數值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(**uint64_t**) override | 將無號 64 位元整數值的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 將指定的字元陣列的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 將指定字元陣列之範圍的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(const char_t *) override | 將指定的 C 字串輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | 將指定的 [TypeInfo](../typeinfo/) 物件的字串表示輸出至目前物件所代表的輸出串流。 |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | 將指定的 32 位元整數值的字串表示寫入串流。 |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | 將指定的值依照指定的格式寫入串流。 |
| void [WriteLine](./writeline/)() override | 將目前的行終止字串輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | 將指定物件的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(**bool**) override | 將指定的 bool 值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(char_t) override | 將指定的字元值，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | 將 [Decimal](../decimal/) 值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(**double**) override | 將雙精度浮點值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(int) override | 將 32 位元整數值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(**int64_t**) override | 將 64 位元整數值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(**float**) override | 將單精度浮點值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | 將指定的字串物件，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(**uint32_t**) override | 將無號 32 位元整數值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(**uint64_t**) override | 將無號 64 位元整數值的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | 將指定的字元陣列的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | 將指定字元陣列之範圍的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(const char_t *) override | 將指定的 C 字串，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | 將指定的 [TypeInfo](../typeinfo/) 物件的字串表示，並在其後加上目前行終止字串，輸出至目前物件所代表的輸出串流。 |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | 將指定的值依照指定的格式寫入串流，並在其後加上換行字元。 |
| virtual  [~Object](../object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | 析構函式。 |

## 另見

* 類別 [TextWriter](../../system.io/textwriter/)
* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)