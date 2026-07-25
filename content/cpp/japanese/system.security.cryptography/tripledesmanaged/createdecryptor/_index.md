---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API リファレンス
description: 明示的なパラメーターで復号化オブジェクトを作成します。
type: docs
weight: 14
url: /ja/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

明示的なパラメーターで復号化オブジェクトを作成します。

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の暗号化キー。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の初期化ベクトル。 |

### 戻り値

新しく作成された復号化オブジェクト。

## TripleDESManaged::CreateDecryptor() method

アルゴリズムオブジェクトで定義されたパラメーターで復号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

アルゴリズムオブジェクトで定義されたパラメーターで復号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../../icryptotransform/)
* クラス [TripleDESManaged](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)