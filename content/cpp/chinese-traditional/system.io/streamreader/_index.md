---
title: StreamReader
second_title: Aspose.Slides for C++ API 參考
description: "表示一個從位元組串流讀取字元的讀取器。此類別的物件應僅透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤與/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 378
url: /zh-hant/system.io/streamreader/
---
## StreamReader 類別

表示一個從位元組串流讀取字元的讀取器。此類別的物件應僅透過 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤與/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class StreamReader : public System::IO::TextReader
```

## 方法

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | 關閉目前及底層的串流。 |
| virtual void [Dispose](./dispose/)(**bool**) | 釋放目前物件使用的所有資源，並關閉底層的串流。 |
| void [Dispose](./dispose/)() override | 釋放目前物件使用的所有資源，並關閉底層的串流。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意來比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | 傳回表示底層串流之物件的共享指標。 |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | 傳回目前使用的編碼。 |
| **bool** [get_EndOfStream](./get_endofstream/)() | 傳回一個表示是否已達串流結尾的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的加鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| int [Peek](./peek/)() override | 從串流讀取單一字元，且不會改變串流的讀取指標。 |
| int [Read](./read/)() override | 從串流讀取單一字元。 |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | 從串流讀取指定數量的字元，將其轉換為 UTF-16 編碼，並將產生的 UTF-16 字元寫入指定的字元陣列，從指定位置開始。 |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | 從目前的文字讀取器讀取指定的最多字元數，並將資料寫入緩衝區，從指定的索引開始。 |
| [String](../../system/string/) [ReadLine](./readline/)() override | 從串流讀取字元，直到目前行的結尾。 |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | 從串流讀取字元，直到串流結尾。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數降低指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | 建構一個 [StreamReader](./) 物件實例，該物件使用 UTF-8 編碼並以 1024 位元組的預設緩衝區，從指定的底層串流讀取字元。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | 建構一個 [StreamReader](./) 物件實例，該物件使用 UTF-8 編碼並以 1024 位元組的預設緩衝區，從指定的底層串流讀取字元。參數指定是否啟用位元順序標記偵測。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 建構一個 [StreamReader](./) 物件實例，該物件使用指定的編碼並以 1024 位元組的預設緩衝區，從指定的底層串流讀取字元。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | 建構一個 [StreamReader](./) 物件實例，該物件使用指定的編碼並以 1024 位元組的預設緩衝區，從指定的底層串流讀取字元。參數指定是否啟用位元順序標記偵測。 |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | 建構一個 [StreamReader](./) 物件實例，該物件使用指定的編碼並以指定大小的緩衝區，從指定的底層串流讀取字元。參數指定是否啟用位元順序標記偵測。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | 建構一個 [StreamReader](./) 物件實例，該物件使用 UTF-8 編碼並以 4096 位元組的預設緩衝區，從指定的檔案讀取字元。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | 建構一個 [StreamReader](./) 物件實例，該物件使用 UTF-8 編碼並以 4096 位元組的預設緩衝區，從指定的檔案讀取字元。參數指定是否啟用位元順序標記偵測。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 建構一個 [StreamReader](./) 物件實例，該物件使用指定的編碼並以 4096 位元組的預設緩衝區，從指定的檔案讀取字元。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | 建構一個 [StreamReader](./) 物件實例，該物件使用指定的編碼並以 4096 位元組的預設緩衝區，從指定的底層串流讀取字元。參數指定是否啟用位元順序標記偵測。 |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | 建構一個 [StreamReader](./) 物件實例，該物件使用指定的編碼並以指定大小的緩衝區，從指定的檔案讀取字元。參數指定是否啟用位元順序標記偵測。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
|  [~StreamReader](./~streamreader/)() | 解構函式。 |

## 另請參閱

* 類別 [TextReader](../textreader/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)