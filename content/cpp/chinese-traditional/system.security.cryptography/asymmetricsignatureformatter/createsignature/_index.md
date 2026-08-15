---
title: CreateSignature()
second_title: Aspose.Slides for C++ API 參考文件
description: 為指定的資料建立簽章。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) 方法

為指定的資料建立簽章。

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) 用於計算雜湊。 |

### 回傳值

以位元組陣列形式計算出的簽章。

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) 方法

為指定的雜湊值建立簽章。

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | 建立簽章時使用的雜湊演算法。 |

### 回傳值

以位元組陣列形式計算出的簽章。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [AsymmetricSignatureFormatter](../)
* 類別 [HashAlgorithm](../../hashalgorithm/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)