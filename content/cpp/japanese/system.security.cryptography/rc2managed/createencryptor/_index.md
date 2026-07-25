---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API リファレンス
description: 明示的なパラメータで暗号化オブジェクトを作成します。
type: docs
weight: 1
url: /ja/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド

明示的なパラメータで暗号化オブジェクトを作成します。

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の暗号化キー。 |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | バイト配列形式の初期値。 |

### 戻り値

新しく作成された暗号化オブジェクト。

## RC2Managed::CreateEncryptor() メソッド

アルゴリズムオブジェクトで定義されたパラメータを使用して暗号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) メソッド

アルゴリズムオブジェクトで定義されたパラメータを使用して暗号化オブジェクトを作成します。

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICryptoTransform](../../icryptotransform/)
* クラス [RC2Managed](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)