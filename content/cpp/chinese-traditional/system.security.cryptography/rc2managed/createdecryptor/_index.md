---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API 參考
description: 建立具有明確參數的解密器物件。
type: docs
weight: 14
url: /zh-hant/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


建立具有明確參數的解密器物件。

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 以位元組陣列形式的加密金鑰。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 以位元組陣列形式的初始向量。 |

### 返回值

新建立的解密器物件。

## RC2Managed::CreateDecryptor() method


建立使用演算法物件定義的參數之解密器物件。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


建立使用演算法物件定義的參數之解密器物件。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICryptoTransform](../../icryptotransform/)
* 類別 [RC2Managed](../)
* 命名空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)