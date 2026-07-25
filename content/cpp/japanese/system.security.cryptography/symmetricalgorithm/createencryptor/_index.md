---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API リファレンス
description: アルゴリズム オブジェクトに関連付けられたパラメータで暗号化器を作成します。
type: docs
weight: 183
url: /ja/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() メソッド

アルゴリズム オブジェクトに関連付けられたパラメーターで暗号化器を作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### 戻り値

新しく作成された暗号化器オブジェクト。

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド

明示的なパラメーターで暗号化器を作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 使用するキー。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 使用する初期値。 |

### 戻り値

新しく作成された暗号化器オブジェクト。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../../icryptotransform/)
* クラス [SymmetricAlgorithm](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)