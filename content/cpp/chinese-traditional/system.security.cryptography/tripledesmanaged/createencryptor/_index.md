---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API 參考
description: 建立具有明確參數的加密器物件。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

建立具有明確參數的加密器物件。

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 以位元組陣列形式表示的加密金鑰。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 以位元組陣列形式表示的初始值。 |

### 傳回值

新建立的加密器物件。

## TripleDESManaged::CreateEncryptor() 方法

建立由演算法物件定義之參數的加密器物件。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

建立由演算法物件定義之參數的加密器物件。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICryptoTransform](../../icryptotransform/)
* 類別 [TripleDESManaged](../)
* 命名空間 [System::Security::Cryptography](../../)
* 程式庫 [Aspose.Slides](../../../)