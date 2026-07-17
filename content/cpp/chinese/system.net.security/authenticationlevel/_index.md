---
title: AuthenticationLevel
second_title: Aspose.Slides for C++ API 参考
description: 特定于 WebRequest 的身份验证标志。
type: docs
weight: 27
url: /zh/system.net.security/authenticationlevel/
---
## AuthenticationLevel 枚举

特定于 WebRequest 的身份验证标志。

```cpp
enum class AuthenticationLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | 客户端和服务器均不需要身份验证。 |
| MutualAuthRequested | 1 | 如果服务器未通过身份验证，请求不会失败。 |
| MutualAuthRequired | 2 | 当服务器未通过身份验证时，当前应用程序将收到 'IOException'。 |

## See Also

* 命名空间 [System::Net::Security](../)
* 库 [Aspose.Slides](../../)