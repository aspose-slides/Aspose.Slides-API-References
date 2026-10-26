---
title: Decrypt()
second_title: Aspose.Slides for C++ API 参考
description: 解密消息。未实现。
type: docs
weight: 105
url: /zh/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) 方法

解密消息。未实现。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/)用于解密。 |
| use_oaep | **bool** | True 使用 OAEP 填充，false 使用 PKCS#1 v1.5 填充。 |

### 返回值

已解密的数据数组。

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 方法

使用指定的填充模式解密输入数据。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/)数组用于解密。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 填充模式。 |

### 返回值

已解密的数据，字节数组格式。

## 另请参阅

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RSACryptoServiceProvider](../)
* 类 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)