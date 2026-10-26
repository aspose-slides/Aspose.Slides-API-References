---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API リファレンス
description: 明示的なパラメータで暗号化オブジェクトを作成します。
type: docs
weight: 1
url: /ja/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド

明示的なパラメータで暗号化オブジェクトを作成します。

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の暗号化キーです。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の初期ベクトルです。 |

### 戻り値

新しく作成された暗号化オブジェクトです。

## TripleDESManaged::CreateEncryptor() メソッド

アルゴリズムオブジェクトが定義するパラメータで暗号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド

アルゴリズムオブジェクトが定義するパラメータで暗号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../../icryptotransform/)
* クラス [TripleDESManaged](../)
* 名前空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)