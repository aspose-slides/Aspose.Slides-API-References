---
title: VerifyData()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデータの署名が有効かどうかを検証します。
type: docs
weight: 92
url: /ja/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| offset | **int32_t** | **data** のオフセット。 |
| count | **int32_t** | ハッシュ化するバイト数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) メソッド

指定されたバイナリ ストリームの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## 参照

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)