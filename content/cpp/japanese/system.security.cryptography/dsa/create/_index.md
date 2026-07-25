---
title: Create()
second_title: Aspose.Slides for C++ APIリファレンス
description: デフォルトのDSAアルゴリズム実装を作成します。
type: docs
weight: 105
url: /ja/system.security.cryptography/dsa/create/
---
## DSA::Create() メソッド

デフォルトの[DSA](../)アルゴリズム実装を作成します。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### 戻り値

[DSA](../) アルゴリズムオブジェクト。

## DSA::Create(const String\&) メソッド

デフォルトの[DSA](../)アルゴリズム実装を作成します。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | 「System.Security.Cryptography.DSACryptoServiceProvider」である必要があります。 |

### 戻り値

[DSA](../) アルゴリズムオブジェクト。

## DSA::Create(int32_t) メソッド

指定されたキーサイズでデフォルトの[DSA](../)アルゴリズム実装を作成します。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | キーサイズ（ビット単位）。 |

## DSA::Create(const DSAParameters\&) メソッド

指定されたパラメータでデフォルトの[DSA](../)アルゴリズム実装を作成します。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | [DSA](../)アルゴリズムのパラメータ。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [DSA](../)
* クラス [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* 名前空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)