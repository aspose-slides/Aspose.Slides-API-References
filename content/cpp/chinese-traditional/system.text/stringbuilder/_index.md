---
title: StringBuilder
second_title: Aspose.Slides for C++ API 參考手冊
description: "緩衝區，用於逐段累積字串。此類型可以作為值類型在堆疊配置，或使用 System::MakeObject() 函式在堆上配置。一旦物件被配置，切勿混用以下兩種情況：嚴禁將 SmartPtr 指標指向堆疊配置的物件。"
type: docs
weight: 326
url: /zh-hant/system.text/stringbuilder/
---
## StringBuilder 類


[Buffer](../../system/buffer/) 以逐段累積字串。本類型可以作為值型別在堆疊配置，或使用 [System::MakeObject()](../../system/makeobject/) 函式在堆上配置。一旦物件被配置，切勿混用以下兩種情況：嚴禁將 [SmartPtr](../../system/smartptr/) 指標指向堆疊配置的物件。

```cpp
class StringBuilder : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | 將字符新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | 將多個字符新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | 將字符陣列新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | 將字符陣列切片新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | 將字串新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | 將字串切片新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | 將物件的字串表示新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | 將建構器的內容新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(**float**) | 將浮點數值新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(**double**) | 將浮點數值新增至建構器。 |
| [StringBuilder](./) * [Append](./append/)(int) | 將整數值新增至建構器。 |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | 將算術值新增至建構器。 |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | 將列舉值的字串表示新增至建構器。 |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | 將格式化字串新增至建構器。 |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | 將格式化字串新增至建構器。 |
| [StringBuilder](./) * [AppendLine](./appendline/)() | 在建構器加入換行字元。 |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | 在建構器加入字串並換行。 |
| [StringBuilder](./) * [Clear](./clear/)() | 移除建構器中的所有字符。 |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | 將建構器資料複製到既有陣列位置。 |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | 確保此 [System.Text.StringBuilder](./) 實例的容量至少為指定值。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較；即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較；即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| int [get_Capacity](./get_capacity/)() const | 取得建構器目前的容量。 |
| int [get_Length](./get_length/)() const | 取得建構器中目前字串的長度。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等價實作。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| char_t [idx_get](./idx_get/)(int) const | 取得指定位置的字符。 |
| void [idx_set](./idx_set/)(int, char_t) | 設定指定位置的字符。 |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | 在建構器的固定位置插入字串。 |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | 在建構器的固定位置插入重複字串。 |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | 在建構器的固定位置插入字符。 |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | 在建構器的固定位置插入字符陣列。 |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | 在建構器的固定位置插入數值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| char_t [operator[]](./operator[]/)(int) const | 取得指定位置的字符。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串的情況。 |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | 從建構器移除片段。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 透過建構器取代子字串。 |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | 於建構器指定範圍內取代子字串。 |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | 於建構器取代字符。 |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | 於建構器指定範圍內取代字符。 |
| void [set_Capacity](./set_capacity/)(int) | 設定建構器目前的容量。 |
| void [set_Length](./set_length/)(int) | 將建構器截斷或延伸至指定長度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器目前的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [StringBuilder](./stringbuilder/)() | 建構函式。 |
|  [StringBuilder](./stringbuilder/)(int) | 建構函式。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | 建構函式。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | 建構函式。 |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | 建構函式。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 取得建構器目前包含的字串。 |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | 取得建構器目前包含的子字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
|  [~StringBuilder](./~stringbuilder/)() | 解構函式。 |

## 另見

* 類 [Object](../../system/object/)
* 命名空間 [System::Text](../)
* 函式庫 [Aspose.Slides](../../)