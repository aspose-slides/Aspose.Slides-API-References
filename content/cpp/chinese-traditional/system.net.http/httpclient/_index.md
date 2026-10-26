---
title: HttpClient
second_title: Aspose.Slides for C++ API 參考
description: "表示用於發送請求和接收回應的 HTTP 客戶端的基礎類別。此類別的物件只能透過 System::MakeObject() 函式配置。絕不要在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 27
url: /zh-hant/system.net.http/httpclient/
---
## HttpClient 類別


表示一個用於發送請求和接收回應的 HTTP 客戶端的基礎類別。此類的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式分配。絕不要在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class HttpClient : public System::Net::Http::HttpMessageInvoker
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [CancelPendingRequests](./cancelpendingrequests/)() | 取消所有未完成的請求。 |
| void [Dispose](../httpmessageinvoker/dispose/)() override | 釋放目前的實例。若有需要，此方法亦會釋放處理程序。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 規範，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 規範，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_BaseAddress](./get_baseaddress/)() | 取得用於發送請求的資源之基礎位址。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Headers::HttpRequestHeaders](../../system.net.http.headers/httprequestheaders/)\> [get_DefaultRequestHeaders](./get_defaultrequestheaders/)() | 取得每個請求所發送的標頭。 |
| **int64_t** [get_MaxResponseContentBufferSize](./get_maxresponsecontentbuffersize/)() | 取得回應內容的最大位元組數。 |
| [TimeSpan](../../system/timespan/) [get_Timeout](./get_timeout/)() | 取得請求逾時前的等待時間跨度。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
|  [HttpClient](./httpclient/)() | 建構新的實例。 |
|  [HttpClient](./httpclient/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>) | 建構新的實例。 |
|  [HttpClient](./httpclient/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>, **bool**) | 建構新的實例。 |
|  [HttpMessageInvoker](../httpmessageinvoker/httpmessageinvoker/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>) | 建構新的實例。 |
|  [HttpMessageInvoker](../httpmessageinvoker/httpmessageinvoker/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMessageHandler](../httpmessagehandler/)\>, **bool**) | 建構新的實例。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](../httpresponsemessage/)\> [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>, [HttpCompletionOption](../httpcompletionoption/)) | 傳送指定的 HTTP 請求。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](../httpresponsemessage/)\> [Send](../httpmessageinvoker/send/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>) | 傳送指定的請求。 |
| void [set_BaseAddress](./set_baseaddress/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 設定用於發送請求的資源之基礎位址。 |
| void [set_MaxResponseContentBufferSize](./set_maxresponsecontentbuffersize/)(**int64_t**) | 設定回應內容的最大位元組數。 |
| void [set_Timeout](./set_timeout/)([TimeSpan](../../system/timespan/)) | 設定請求逾時前的等待時間跨度。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共用參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [HttpMessageInvoker](../httpmessageinvoker/)
* 命名空間 [System::Net::Http](../)
* 函式庫 [Aspose.Slides](../../)