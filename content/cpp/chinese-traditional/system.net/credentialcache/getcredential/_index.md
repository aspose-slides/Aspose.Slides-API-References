---
title: GetCredential()
second_title: Aspose.Slides C++ API 參考
description: 返回指定 URI 前綴和驗證類型的憑證。
type: docs
weight: 66
url: /zh-hant/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) method


返回指定 URI 前綴和驗證類型的憑證。

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI 前綴。 |
| authenticationType | [String](../../../system/string/) | 驗證類型。 |

## CredentialCache::GetCredential(String, int32_t, String) method


返回指定主機名稱、埠號和驗證類型的憑證。

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | 與憑證相關聯的主機名稱。 |
| port | **int32_t** | 埠號。 |
| authenticationType | [String](../../../system/string/) | 驗證類型。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)