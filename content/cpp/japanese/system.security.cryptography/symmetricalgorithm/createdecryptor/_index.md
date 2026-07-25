---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API リファレンス
description: アルゴリズムオブジェクトに関連付けられたパラメータで復号化器を作成します。
type: docs
weight: 196
url: /ja/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() メソッド


アルゴリズムオブジェクトに関連付けられたパラメータで復号化器を作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### 戻り値

新しく作成された復号化器オブジェクト。

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド


明示的なパラメータで復号化器を作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 使用するキー。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 使用する初期値。 |

### 戻り値

新しく作成された復号化器オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../../icryptotransform/)
* クラス [SymmetricAlgorithm](../)
* 名前空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)