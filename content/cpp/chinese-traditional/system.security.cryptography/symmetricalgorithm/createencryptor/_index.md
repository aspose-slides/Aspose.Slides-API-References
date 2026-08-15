---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用與演算法物件相關的參數建立加密器。
type: docs
weight: 183
url: /zh-hant/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() 方法

建立具有與演算法物件關聯之參數的加密器。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### 返回值

新建立的加密器物件。

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

建立具有明確參數的加密器。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 使用的金鑰。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 使用的初始值。 |

### 返回值

新建立的加密器物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICryptoTransform](../../icryptotransform/)
* 類別 [SymmetricAlgorithm](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)