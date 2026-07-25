---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API リファレンス
description: 明示的なパラメータで復号化オブジェクトを作成します。
type: docs
weight: 14
url: /ja/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド


明示的なパラメータで復号化オブジェクトを作成します。

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の暗号化キー。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の初期ベクトル。 |

### 戻り値

新しく作成された復号化オブジェクト。

## RijndaelManaged::CreateDecryptor() メソッド


アルゴリズムオブジェクトで定義されたパラメータで復号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド


アルゴリズムオブジェクトで定義されたパラメータで復号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../../icryptotransform/)
* クラス [RijndaelManaged](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)