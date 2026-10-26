---
title: VerifyData()
second_title: Aspose.Slides for C++ API リファレンス
description: データの署名をチェックします。
type: docs
weight: 209
url: /ja/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


データの署名を確認します。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) の署名を確認するための。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 受信した署名。 |

### 戻り値

署名が有効な場合は true、そうでない場合は false。

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true、そうでない場合は false。 |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


指定されたデータの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名されたデータ。 |
| offset | **int32_t** | データ内のオフセット。 |
| count | **int32_t** | ハッシュ化するバイト数。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true、そうでない場合は false。 |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


指定されたバイナリストリームの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 署名されたデータ。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。署名が有効な場合は true、そうでない場合は false。 |

## 参考

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [StreamPtr](../../../system/streamptr/)
* クラス [DSACryptoServiceProvider](../)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)