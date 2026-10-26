---
title: GetCredential()
second_title: Aspose.Slides for C++ API 参考
description: 返回指定主机和身份验证类型的凭据。
type: docs
weight: 1
url: /zh/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) 方法

返回指定主机和身份验证类型的凭据。

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 对客户端进行身份验证的主机。 |
| port | **int32_t** | 主机端口号。 |
| authenticationType | [String](../../../system/string/) | 身份验证类型。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [NetworkCredential](../../networkcredential/)
* 类 [String](../../../system/string/)
* 类 [ICredentialsByHost](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)