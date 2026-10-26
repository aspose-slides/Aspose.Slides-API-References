---
title: GetCredential()
second_title: Aspose.Slides for C++ API 参考
description: 返回指定 URI 和身份验证类型的凭据。
type: docs
weight: 92
url: /zh/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) 方法

返回指定 URI 和身份验证类型的凭据。

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI。 |
| authenticationType | [String](../../../system/string/) | 身份验证类型。 |

## NetworkCredential::GetCredential(String, int32_t, String) 方法

返回指定主机名、端口和身份验证类型的凭据。

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 主机名。 |
| port | **int32_t** | 端口号。 |
| authenticationType | [String](../../../system/string/) | 身份验证类型。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [NetworkCredential](../)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)