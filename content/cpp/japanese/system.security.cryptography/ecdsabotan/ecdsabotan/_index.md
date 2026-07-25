---
title: ECDsaBotan()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。デフォルトパラメータを使用します。
type: docs
weight: 1
url: /ja/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() コンストラクタ


コンストラクタ。デフォルトパラメータを使用します。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | アルゴリズムのパラメータ。 |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | 公開/非公開鍵ペアを作成するために使用される曲線。 |

## ECDsaBotan::ECDsaBotan(int32_t) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key_size | **int32_t** | ビット単位のキーサイズ。 |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan の公開鍵。 |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan の秘密鍵。 |

## 参照

* クラス [ECDsaBotan](../)
* 構造体 [ECParameters](../../ecparameters/)
* 構造体 [ECCurve](../../eccurve/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)