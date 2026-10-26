---
title: X509KeyStorageFlags
second_title: Aspose.Slides for C++ API 参考
description: 定义如何存储密钥。
type: docs
weight: 261
url: /zh/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags 枚举

定义如何存储密钥。

```cpp
enum class X509KeyStorageFlags : int32_t
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| DefaultKeySet | 0 | 使用默认密钥集合。 |
| UserKeySet | 1 | 使用用户关联的存储区而不是机器本地的存储区。 |
| MachineKeySet | 2 | 使用本地机器存储而不是用户存储。 |
| Exportable | 4 | 标记导入的密钥为可导出。 |
| UserProtected | 8 | 通知用户密钥正在被使用。 |
| PersistKeySet | 16 | 在导入证书时，密钥会被持久化。 |

## 另见

* 命名空间 [System::Security::Cryptography::X509Certificates](../)
* 库 [Aspose.Slides](../../)