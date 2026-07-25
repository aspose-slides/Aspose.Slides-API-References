---
title: VerifyData()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデータの署名が有効かどうかを検証します。
type: docs
weight: 157
url: /ja/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | パディングモード。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| offset | **int32_t** | **data** のオフセット。 |
| count | **int32_t** | ハッシュ対象のバイト数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | パディングモード。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) メソッド

指定されたバイナリ ストリームの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | パディングモード。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## 参照

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* クラス [RSASignaturePadding](../../rsasignaturepadding/)
* クラス [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)