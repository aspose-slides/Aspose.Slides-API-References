---
title: HttpRequestMessage
second_title: Aspose.Slides for C++ API 參考
description: "表示 HTTP 請求訊息。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 105
url: /zh-hant/system.net.http/httprequestmessage/
---
## HttpRequestMessage 類別

表示 HTTP 請求訊息。此類別的物件僅應使用 [System::MakeObject()](../../system/makeobject/) 函式進行配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class HttpRequestMessage : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Dispose](./dispose/)() override | 釋放當前實例。此方法還會釋放 HTTP 請求的內容。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\> [get_Content](./get_content/)() | 取得 HTTP 請求的內容。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Http::Headers::HttpRequestHeaders](../../system.net.http.headers/httprequestheaders/)\> [get_Headers](./get_headers/)() | 返回 HTTP 內容標頭。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\> [get_Method](./get_method/)() | 取得 HTTP 請求的方法。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Properties](./get_properties/)() | 返回 HTTP 請求屬性的集合。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() | 取得請求資源的 URI。 |
| [System::Version](../../system/version/) [get_Version](./get_version/)() | 取得 HTTP 版本。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參照計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。支援自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
|  [HttpRequestMessage](./httprequestmessage/)() | 建構新實例。 |
|  [HttpRequestMessage](./httprequestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 建構新實例。 |
|  [HttpRequestMessage](./httprequestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>, [String](../../system/string/)) | 建構新實例。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| **bool** [MarkAsSent](./markassent/)() | 標記目前請求為已發送。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。支援自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| void [set_Content](./set_content/)([System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\>) | 設定 HTTP 請求的內容。 |
| void [set_Method](./set_method/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>) | 設定 HTTP 請求的方法。 |
| void [set_RequestUri](./set_requesturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 設定請求資源的 URI。 |
| void [set_Version](./set_version/)([System::Version](../../system/version/)) | 設定 HTTP 版本。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個範本參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參照計數。請勿直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並返回共享參照計數。請勿直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。支援將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參照計數。請勿直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參照計數。請勿直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 參見

* 類別 [IDisposable](../../system/idisposable/)
* 命名空間 [System::Net::Http](../)
* 函式庫 [Aspose.Slides](../../)