---
title: TryFromOid()
second_title: Aspose.Slides C++ API 参考
description: 尝试使用 OID 值创建 HashAlgorithmName。
type: docs
weight: 66
url: /zh/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) 方法

尝试从 OID 值创建 [HashAlgorithmName](../)。

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID 值。 |
| value | [HashAlgorithmName](../)\& | 输出 [HashAlgorithmName](../)。 |

### 返回值

如果指定的 OID 是有效的哈希算法，则返回 true；否则返回 false。

## 另请参阅

* 类 [String](../../../system/string/)
* 结构体 [HashAlgorithmName](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)