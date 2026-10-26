---
title: VerifyHash()
second_title: Aspose.Slides C++ API 参考
description: 检查数据签名。
type: docs
weight: 183
url: /zh/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) 方法

检查数据签名。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 为接收的数据计算的哈希。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 接收到的签名。 |

### 返回值

如果签名有效则为 True，否则为 false。

## 另请参见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [ECDsaBotan](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)