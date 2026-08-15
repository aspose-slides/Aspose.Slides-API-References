---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 移除指定 URI 前置詞和驗證類型的網路憑證。
type: docs
weight: 53
url: /zh-hant/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) 方法

移除指定 URI 前置詞和驗證類型的網路憑證。

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI 前置詞。 |
| authenticationType | [String](../../../system/string/) | 驗證類型。 |

## CredentialCache::Remove(String, int32_t, String) 方法

移除指定主機名稱、埠號和驗證類型的網路憑證。

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 與憑證相關聯的主機名稱。 |
| port | **int32_t** | 埠號。 |
| authenticationType | [String](../../../system/string/) | 驗證類型。 |

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [CredentialCache](../)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)