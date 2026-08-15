---
title: CacheControlHeaderValue
second_title: Aspose.Slides for C++ API 參考
description: "表示 'Cache-Control' 標頭的值。此類別的物件應僅使用 System::MakeObject() 函式進行配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用該指標將其作為參數傳遞給函式。"
type: docs
weight: 14
url: /zh-hant/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue 類別


代表 'Cache-Control' 標頭的值。此類別的物件應只能使用 [System::MakeObject()](../../system/makeobject/) 函式進行配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標將其作為參數傳遞給函式。

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | 建立新實例。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | 返回快取擴充標記的集合。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | 取得以秒為單位的最大存活時間值，決定客戶端接受回應的時間長度。 |
| **bool** [get_MaxStale](./get_maxstale/)() | 取得決定客戶端是否接受過期回應的值。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | 取得以秒為單位的值，決定客戶端接受過期回應的時間長度。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | 取得決定新鮮度生命週期的值。 |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | 取得決定伺服器在快取項目變陳舊時是否需要重新驗證的值。 |
| **bool** [get_NoCache](./get_nocache/)() | 取得決定客戶端是否接受快取回應的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | 取得 'Cache-Control' 標頭中 'no-cache' 指令的欄位名稱集合。 |
| **bool** [get_NoStore](./get_nostore/)() | 取得決定快取不得儲存任何 HTTP 請求或回應部分的值。 |
| **bool** [get_NoTransform](./get_notransform/)() | 取得決定快取或代理不得更改實體內容任何部分的值。 |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | 取得決定客戶端必須僅使用快取條目的值。 |
| **bool** [get_Private](./get_private/)() | 取得決定 HTTP 回應訊息或其部分僅供單一使用者且不可由共享快取儲存的值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | 取得 'Cache-Control' 標頭中 'private' 指令的欄位名稱集合。 |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | 取得決定伺服器在共享使用者代理快取變陳舊時是否需要重新驗證快取項目的值。 |
| **bool** [get_Public](./get_public/)() | 取得決定 HTTP 回應是否可被任何快取儲存的值。 |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | 取得共享快取的最大存活時間（以秒為單位），會覆寫 'Cache-Control' 中的 'max-age' 指令或 'Expires' 標頭。 |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 將傳入的字串從指定索引轉換為 [CacheControlHeaderValue](./) 類別的實例。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | 將傳入的字串轉換為 [CacheControlHeaderValue](./) 類別的實例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 的情況，[Object::ReferenceEquals](../../system/object/referenceequals/) 的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串的情況，[Object::ReferenceEquals](../../system/object/referenceequals/) 的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 設定以秒為單位的最大存活時間值，決定客戶端接受回應的時間長度。 |
| void [set_MaxStale](./set_maxstale/)(**bool**) | 設定決定客戶端是否接受過期回應的值。 |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 設定以秒為單位的值，決定客戶端接受過期回應的時間長度。 |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 設定決定新鮮度生命週期的值。 |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | 設定決定伺服器在快取項目變陳舊時是否需要重新驗證的值。 |
| void [set_NoCache](./set_nocache/)(**bool**) | 設定決定客戶端是否接受快取回應的值。 |
| void [set_NoStore](./set_nostore/)(**bool**) | 設定決定快取不得儲存任何 HTTP 請求或回應部分的值。 |
| void [set_NoTransform](./set_notransform/)(**bool**) | 設定決定快取或代理不得更改實體內容任何部分的值。 |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | 設定決定客戶端必須僅使用快取條目的值。 |
| void [set_Private](./set_private/)(**bool**) | 設定決定 HTTP 回應訊息或其部分僅供單一使用者且不可由共享快取儲存的值。 |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | 設定決定伺服器在共享使用者代理快取變陳舊時是否需要重新驗證快取項目的值。 |
| void [set_Public](./set_public/)(**bool**) | 設定決定 HTTP 回應是否可被任何快取儲存的值。 |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | 設定共享快取的最大存活時間（以秒為單位），會覆寫 'Cache-Control' 中的 'max-age' 指令或 'Expires' 標頭。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | 嘗試將傳入的字串轉換為 [CacheControlHeaderValue](./) 類別的實例。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 參見

* 類別 [ICloneable](../../system/icloneable/)
* 命名空間 [System::Net::Http::Headers](../)
* 程式庫 [Aspose.Slides](../../)