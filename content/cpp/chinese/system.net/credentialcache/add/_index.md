---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 将指定的网络凭据添加到缓存中。
type: docs
weight: 40
url: /zh/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) 方法

将指定的网络凭据添加到缓存中。

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 与凭据关联的资源的 URI 前缀。 |
| authenticationType | [String](../../../system/string/) | 身份验证方案。 |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 要添加的凭据。 |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) 方法

将指定的网络凭据添加到缓存中。

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 与凭据关联的主机名。 |
| port | **int32_t** | 端口号。 |
| authenticationType | [String](../../../system/string/) | 身份验证方案。 |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 要添加的凭据。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [NetworkCredential](../../networkcredential/)
* 类 [CredentialCache](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)