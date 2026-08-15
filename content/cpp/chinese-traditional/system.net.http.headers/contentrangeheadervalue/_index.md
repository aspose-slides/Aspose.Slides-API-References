---
title: ContentRangeHeaderValue
second_title: Aspose.Slides for C++ API 參考文件
description: "表示 'Content-Range' 標頭的值。此類別的物件只能使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝為 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 40
url: /zh-hant/system.net.http.headers/contentrangeheadervalue/
---
## ContentRangeHeaderValue 類別


表示 'Content-Range' 標頭的值。此類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式進行配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝為 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。

```cpp
class ContentRangeHeaderValue : public System::ICloneable
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**, **int64_t**, **int64_t**) | 建立新實例。 |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**) | 建立新實例。 |
|  [ContentRangeHeaderValue](./contentrangeheadervalue/)(**int64_t**, **int64_t**) | 建立新實例。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_From](./get_from/)() | 取得資料傳送必須開始的位置。 |
| **bool** [get_HasLength](./get_haslength/)() const | 取得表示目前標頭是否已指定長度的值。 |
| **bool** [get_HasRange](./get_hasrange/)() const | 取得表示目前標頭是否已指定範圍的值。 |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Length](./get_length/)() | 取得實體主體的長度。 |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_To](./get_to/)() | 取得資料傳送必須停止的位置。 |
| [String](../../system/string/) [get_Unit](./get_unit/)() | 取得範圍中使用的單位。 |
| static **int32_t** [GetContentRangeLength](./getcontentrangelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 將傳入的字串從指定位置轉換為 [ContentRangeHeaderValue](./) 類別的實例。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與該物件相關聯的參考計數器資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 將傳入的字串轉換為 [ContentRangeHeaderValue](./) 類別的實例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Unit](./set_unit/)([String](../../system/string/)) | 設定範圍中使用的單位。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentRangeHeaderValue](./)\>\&) | 嘗試將傳入的字串轉換為 [ContentRangeHeaderValue](./) 類別的實例。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [ICloneable](../../system/icloneable/)
* 命名空間 [System::Net::Http::Headers](../)
* 函式庫 [Aspose.Slides](../../)