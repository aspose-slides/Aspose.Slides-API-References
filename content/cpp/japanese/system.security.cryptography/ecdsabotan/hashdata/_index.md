---
title: HashData()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたハッシュアルゴリズムを使用して、指定されたデータ配列のハッシュ値を計算します。
type: docs
weight: 105
url: /ja/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


指定されたデータ配列のハッシュ値を、指定されたハッシュアルゴリズムを使用して計算します。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) をハッシュする。 |
| offset | **int32_t** | **data** のオフセット。 |
| count | **int32_t** | ハッシュするバイト数。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | ハッシュアルゴリズム。 |

### 戻り値

ハッシュされたデータ。

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


指定されたバイナリストリームのハッシュ値を、指定されたハッシュアルゴリズムを使用して計算します。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | ハッシュするバイナリストリーム。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | ハッシュアルゴリズム。 |

### 戻り値

ハッシュされたデータ。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [StreamPtr](../../../system/streamptr/)
* クラス [ECDsaBotan](../)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)