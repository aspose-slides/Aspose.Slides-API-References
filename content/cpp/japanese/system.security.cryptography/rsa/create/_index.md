---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトの RSA アルゴリズム実装を作成します。
type: docs
weight: 183
url: /ja/system.security.cryptography/rsa/create/
---
## RSA::Create() メソッド


デフォルトの [RSA](../) アルゴリズム実装を作成します。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) メソッド


デフォルトの [RSA](../) アルゴリズム実装を作成します。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | \"System.Security.Cryptography.RSACryptoServiceProvider\" である必要があります。 |

## RSA::Create(int32_t) メソッド


デフォルトの [RSA](../) アルゴリズム実装を作成します（指定されたキーサイズ）。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | キーサイズ（ビット単位）。 |

## RSA::Create(const RSAParameters\&) メソッド


デフォルトの [RSA](../) アルゴリズム実装を作成します（指定されたパラメータ）。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | [RSA](../) アルゴリズムのパラメータ。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RSA](../)
* クラス [String](../../../system/string/)
* 構造体 [RSAParameters](../../rsaparameters/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)