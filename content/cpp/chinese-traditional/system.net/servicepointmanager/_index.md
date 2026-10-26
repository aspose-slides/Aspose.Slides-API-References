---
title: ServicePointManager
second_title: Aspose.Slides for C++ API 參考
description: "管理 ServicePoint 類別實例的生命週期階段（建立、維護與刪除）。此類別的物件應僅使用 System::MakeObject() 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 430
url: /zh-hant/system.net/servicepointmanager/
---
## ServicePointManager 類別


管理 [ServicePoint](../servicepoint/) 類別實例的生命週期階段（建立、維護與刪除）。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class ServicePointManager : public System::Object
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | 取得憑證政策。 |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | 取得指示是否必須根據憑證授權機構撤銷清單檢查憑證的值。 |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | 取得 ServicePoint-class 實例允許的最大同時連線數。 |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | 取得 DNS 解析被視為有效的毫秒超時時間。 |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | 取得指示 DNS 解析是否在可用 IP 位址之間輪替的值。 |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | 傳回目前實例所使用的加密政策。 |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | 取得指示 ServicePoint-class 實例是否使用 100-Continue 行為的值。 |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | 取得 ServicePoint-class 實例的最大閒置時間。 |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | 取得目前實例可管理的 ServicePoint-class 實例的最大數量。 |
| static **bool** [get_ReusePort](./get_reuseport/)() | 取得指示輸出連線套接字是否使用 'SO_REUSE_UNICASTPORT' 選項的值。 |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | 取得目前實例所管理的 ServicePoint-class 實例使用的安全協定類型。 |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | 取得用於驗證伺服器憑證的回呼函式。 |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | 取得指示 ServicePoint-class 實例是否使用 Nagle 演算法的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共用參考計數。 |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | 設定憑證政策。 |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | 設定指示是否必須根據憑證授權機構撤銷清單檢查憑證的值。 |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | 設定 ServicePoint-class 實例允許的最大同時連線數。 |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | 設定 DNS 解析被視為有效的毫秒超時時間。 |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | 設定指示 DNS 解析是否在可用 IP 位址之間輪替的值。 |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | 設定指示 ServicePoint-class 實例是否使用 100-Continue 行為的值。 |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | 設定 ServicePoint-class 實例的最大閒置時間。 |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | 設定目前實例可管理的 ServicePoint-class 實例的最大數量。 |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | 設定指示輸出連線套接字是否使用 'SO_REUSE_UNICASTPORT' 選項的值。 |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | 設定目前實例所管理的 ServicePoint-class 實例使用的安全協定類型。 |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | 設定用於驗證伺服器憑證的回呼函式。 |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | 設定指示 ServicePoint-class 實例是否使用 Nagle 演算法的值。 |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 設定指示是否啟用 'Keep-Alive' 選項的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| Field | Description |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | 預設的非持久性連線數量。 |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | 預設的持久性連線數量。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Net](../)
* 程式庫 [Aspose.Slides](../../)