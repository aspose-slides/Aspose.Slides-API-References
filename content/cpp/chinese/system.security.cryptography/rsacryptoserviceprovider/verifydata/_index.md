---
title: VerifyData()
second_title: Aspose.Slides for C++ API 参考
description: 检查数据签名。
type: docs
weight: 209
url: /zh/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method

检查数据签名。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) 用于检查签名。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要使用的哈希算法。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 接收到的签名。 |

### 返回值

如果签名有效则为 true，否则为 false。

## 另见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [RSACryptoServiceProvider](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)