---
title: VerifyData()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 指定されたデータの署名が有効かどうかを検証します。
type: docs
weight: 170
url: /ja/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| offset | **int32_t** | **data** のオフセット。 |
| count | **int32_t** | ハッシュするバイト数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) メソッド

指定されたバイナリストリームの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) メソッド

指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| offset | **int32_t** | **data** のオフセット。 |
| count | **int32_t** | ハッシュするバイト数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) メソッド

指定されたバイナリストリームの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。署名が有効な場合は true を返し、そうでない場合は false を返します。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [StreamPtr](../../../system/streamptr/)
* クラス [ECDsaBotan](../)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)