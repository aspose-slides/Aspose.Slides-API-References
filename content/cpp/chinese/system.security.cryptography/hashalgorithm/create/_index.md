---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 根据名称创建哈希算法。
type: docs
weight: 118
url: /zh/system.security.cryptography/hashalgorithm/create/
---
## HashAlgorithm::Create(const String\&) 方法

基于名称创建哈希算法。

```cpp
static SharedPtr<HashAlgorithm> System::Security::Cryptography::HashAlgorithm::Create(const String &hashName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hashName | const [String](../../../system/string/)\& | 以下值之一：\"MD5\", \"SHA1\", \"SHA256\", \"SHA384\", \"SHA512\", \"RIPEMD160\" 或在前面加上 \"System.Security.Cryptography.\" 前缀的任意上述值。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [HashAlgorithm](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)