---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 参考
description: 验证数据的签名。
type: docs
weight: 27
url: /zh/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法


验证数据的签名。

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) 使用 **rgbSignature** 签名。 |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于验证数据的签名。 |

### 返回值

如果签名检查成功则返回 True，否则返回 false。

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) 方法


验证数据的签名。未实现。

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | 用于散列的算法。 |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于验证数据的签名。 |

### 返回值

如果签名检查成功则返回 True，否则返回 false。

## 参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [AsymmetricSignatureDeformatter](../)
* 类 [HashAlgorithm](../../hashalgorithm/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)