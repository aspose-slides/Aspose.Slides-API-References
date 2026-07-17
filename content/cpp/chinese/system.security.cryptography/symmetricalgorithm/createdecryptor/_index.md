---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API 参考
description: 使用与算法对象关联的参数创建解密器。
type: docs
weight: 196
url: /zh/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() 方法

创建具有与算法对象关联的参数的解密器。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### 返回值

新创建的解密器对象。

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

创建具有显式参数的解密器。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要使用的密钥。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要使用的初始值。 |

### 返回值

新创建的解密器对象。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ICryptoTransform](../../icryptotransform/)
* 类 [SymmetricAlgorithm](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)