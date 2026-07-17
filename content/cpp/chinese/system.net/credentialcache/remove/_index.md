---
title: Remove()
second_title: Aspose.Slides C++ API 参考
description: 移除针对指定 URI 前缀和身份验证类型的网络凭据。
type: docs
weight: 53
url: /zh/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) 方法

移除针对指定 URI 前缀和身份验证类型的网络凭据。

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI 前缀。 |
| authenticationType | [String](../../../system/string/) | 身份验证类型。 |

## CredentialCache::Remove(String, int32_t, String) 方法

移除针对指定主机名、端口和身份验证类型的网络凭据。

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 与凭据关联的主机名。 |
| port | **int32_t** | 端口号。 |
| authenticationType | [String](../../../system/string/) | 身份验证类型。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [CredentialCache](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)