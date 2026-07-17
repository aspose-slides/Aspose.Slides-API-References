---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 参考
description: 检查数据签名。
type: docs
weight: 118
url: /zh/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) 方法


检查数据签名。

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 接收数据的哈希值。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 接收的签名。 |

### 返回值

如果签名有效则返回 true，否则返回 false。

## 另请参见

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [ECDsa](../)
* 命名空间 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)