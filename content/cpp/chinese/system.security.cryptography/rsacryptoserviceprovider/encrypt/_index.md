---
title: Encrypt()
second_title: Aspose.Slides for C++ API 参考
description: 加密消息。未实现。
type: docs
weight: 118
url: /zh/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) 方法

加密消息。未实现。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) 用于加密。 |
| use_oaep | **bool** | True 使用 OAEP 填充，false 使用 PKCS#1 v1.5 填充。 |

### 返回值

加密的数据数组。

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 方法

使用指定的填充模式加密输入数据。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 用于加密的数组。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 填充模式。 |

### 返回值

以字节数组格式的加密数据。

## 参见

* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RSACryptoServiceProvider](../)
* 类 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)