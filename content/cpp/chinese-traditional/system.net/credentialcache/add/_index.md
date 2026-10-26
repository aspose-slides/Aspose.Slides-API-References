---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的網路認證新增至快取。
type: docs
weight: 40
url: /zh-hant/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) 方法

將指定的網路認證新增至快取。

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 與認證關聯的資源 URI 前綴。 |
| authenticationType | [String](../../../system/string/) | 驗證機制。 |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 要新增的認證。 |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) 方法

將指定的網路認證新增至快取。

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 與認證關聯的主機名稱。 |
| port | **int32_t** | 埠號。 |
| authenticationType | [String](../../../system/string/) | 驗證機制。 |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 要新增的認證。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [NetworkCredential](../../networkcredential/)
* 類別 [CredentialCache](../)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)