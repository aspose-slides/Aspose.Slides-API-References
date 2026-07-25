---
title: SignData()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたハッシュアルゴリズムとパディングを使用して、指定されたデータ配列のハッシュ値を計算し、その結果に署名します。
type: docs
weight: 131
url: /ja/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) メソッド

指定されたハッシュアルゴリズムとパディングを使用して、指定されたデータ配列のハッシュ値を計算し、その結果に署名します。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 入力データ配列。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | パディングモード。入力データに対して [RSA](../) 署名を返します。 |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) メソッド

指定されたハッシュアルゴリズムとパディングを使用して、指定されたデータ配列のハッシュ値を計算し、その結果に署名します。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 入力データ配列。 |
| offset | **int32_t** | **data** のオフセット。 |
| count | **int32_t** | 入力データとして使用するバイト数。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | パディングモード。入力データに対して [RSA](../) 署名を返します。 |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) メソッド

指定されたハッシュアルゴリズムとパディングを使用して、指定されたバイナリストリームのハッシュ値を計算し、その結果に署名します。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | バイナリストリーム。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | パディングモード。入力データに対して [RSA](../) 署名を返します。 |

## 関連項目

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [StreamPtr](../../../system/streamptr/)
* クラス [RSASignaturePadding](../../rsasignaturepadding/)
* クラス [RSA](../)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)