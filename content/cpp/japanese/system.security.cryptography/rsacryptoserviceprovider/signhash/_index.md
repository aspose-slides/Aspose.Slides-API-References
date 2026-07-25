---
title: SignHash()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたハッシュ値の署名を計算します。
type: docs
weight: 196
url: /ja/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) メソッド

指定されたハッシュ値の署名を計算します。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | ハッシュ値。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | ハッシュアルゴリズム。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | パディングモード。指定されたハッシュの [RSA](../../rsa/) 署名を返します。 |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) メソッド

指定された入力値の署名を計算します。未実装です。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名対象データのハッシュ値。 |
| str | const [String](../../../system/string/)\& | ハッシュを生成する際に使用されたハッシュアルゴリズムの識別子。 |

### 戻り値

[RSA](../../rsa/) 署名（指定されたデータ）

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RSASignaturePadding](../../rsasignaturepadding/)
* クラス [RSACryptoServiceProvider](../)
* クラス [String](../../../system/string/)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)