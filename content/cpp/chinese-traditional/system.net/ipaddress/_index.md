---
title: IPAddress
second_title: Aspose.Slides for C++ API 參考文件
description: "表示 IP 位址。此類別的物件應僅使用 System::MakeObject() 函式配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝在 System::SmartPtr 指標中，並使用此指標作為參數傳遞給函式。"
type: docs
weight: 326
url: /zh-hant/system.net/ipaddress/
---
## IPAddress 類別


表示 IP 位址。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式來配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裹在 [System::SmartPtr](../../system/smartptr/) 指標中，並使用此指標作為參數傳遞給函式。

```cpp
class IPAddress : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | 傳回位址族群。 |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | 傳回指示此位址是否為 IPv4 位址且已映射至 IPv6 位址的值。 |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | 傳回指示此位址是否為 IPv6 連結本機位址的值。 |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | 傳回指示此位址是否為全域 IPv6 多播位址的值。 |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | 傳回指示此位址是否為 IPv6 站點本機位址的值。 |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | 傳回指示此位址是否為 IPv6 Teredo 位址的值。 |
| **int64_t** [get_ScopeId](./get_scopeid/)() | 取得 IPv6 位址的範圍識別碼。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | 傳回 IP 位址的位元組陣列。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | 傳回指向實作的指標。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | 將指定的主機位元組順序轉換為相應的網路位元組順序。 |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | 將指定的主機位元組順序轉換為相應的網路位元組順序。 |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | 將指定的主機位元組順序轉換為相應的網路位元組順序。 |
| [IPAddress](./ipaddress/)(**int64_t**) | 建立新實例。 |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | 建立新實例。 |
| [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 建立新實例。 |
| [IPAddress](./ipaddress/)() | 建立新實例。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 'is' 運算子。 |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | 傳回指示指定位址是否為迴送位址的值。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | 將位址映射至 IPv4 位址。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | 將位址映射至 IPv6 位址。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | 將指定的網路位元組順序轉換為相應的主機位元組順序。 |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | 將指定的網路位元組順序轉換為相應的主機位元組順序。 |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | 將指定的網路位元組順序轉換為相應的主機位元組順序。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | 將傳入的字串轉換為 [IPAddress](./) 類別的實例。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化版。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化版。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | 設定 IPv6 位址的範圍識別碼。 |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | 設定指向實作的指標。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | 嘗試將傳入的字串轉換為 [IPAddress](./) 類別的實例。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Any](./any/) | 指示伺服器必須監聽所有網路介面的 IPv4 位址。 |
| static [Broadcast](./broadcast/) | IPv4 廣播位址。 |
| static [IPv6Any](./ipv6any/) | 指示伺服器必須監聽所有網路介面的 IPv6 位址。 |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 迴送位址。 |
| static [IPv6None](./ipv6none/) | 指示伺服器不應監聽任何網路介面的 IPv6 位址。 |
| static [Loopback](./loopback/) | IPv4 迴送位址。 |
| static [None](./none/) | 指示伺服器不應監聽任何網路介面的 IPv4 位址。 |

## 型別定義

| 型別別名 | 說明 |
| --- | --- |
| [ImplPtr](./implptr/) | 指向實作型別的指標。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Net](../)
* 函式庫 [Aspose.Slides](../../)