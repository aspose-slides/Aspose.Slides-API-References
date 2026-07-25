---
title: SignData()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された入力値の署名を計算します。
type: docs
weight: 183
url: /ja/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) メソッド

指定された入力値の署名を計算します。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) から入力データを読み取ります。 |

### 戻り値

[DSA](../../dsa/) 指定されたデータの署名。

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) メソッド

指定された入力値の署名を計算します。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 署名対象のデータを読み取るストリーム。 |

### 戻り値

[DSA](../../dsa/) 指定されたデータの署名。

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) メソッド

指定された入力値の署名を計算します。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) から入力データを読み取ります。 |
| offset | **int32_t** | 入力バッファスライスの開始インデックス。 |
| count | **int32_t** | 入力バッファスライスのサイズ。 |

### 戻り値

[DSA](../../dsa/) 指定されたデータの署名。

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) メソッド

指定されたハッシュアルゴリズムを使用して、指定されたデータ配列のハッシュ値を計算し、結果に署名します。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 入力データ配列。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。入力データの [DSA](../../dsa/) 署名を返します。 |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) メソッド

指定されたハッシュアルゴリズムを使用して、指定されたデータ配列のハッシュ値を計算し、結果に署名します。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 入力データ配列。 |
| offset | **int32_t** | **data** のオフセット。 |
| count | **int32_t** | 入力データとして使用するバイト数。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。入力データの [DSA](../../dsa/) 署名を返します。 |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) メソッド

指定されたハッシュアルゴリズムを使用して、指定されたバイナリストリームのハッシュ値を計算し、結果に署名します。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | バイナリストリーム。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。入力データの [DSA](../../dsa/) 署名を返します。 |

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [StreamPtr](../../../system/streamptr/)
* クラス [DSACryptoServiceProvider](../)
* クラス [Stream](../../../system.io/stream/)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)