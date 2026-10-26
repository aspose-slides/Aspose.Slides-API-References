---
title: EncryptionPolicy
second_title: Aspose.Slides for C++ API 参考
description: 枚举加密策略。
type: docs
weight: 53
url: /zh/system.net.security/encryptionpolicy/
---
## EncryptionPolicy 枚举

枚举加密策略。

```cpp
enum class EncryptionPolicy
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| RequireEncryption | 0 | 要求加密，并且永不允许使用 'Null' 密码。 |
| AllowNoEncryption | 1 | 倾向使用完整加密，但如果服务器同意，可以使用 'Null' 密码。 |
| NoEncryption | 2 | 允许不加密，并在对端能够处理 'Null' 密码时请求使用 'Null' 密码。 |

## 另见

* 命名空间 [System::Net::Security](../)
* 库 [Aspose.Slides](../../)