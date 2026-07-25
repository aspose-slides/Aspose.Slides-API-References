---
title: VerifyHash()
second_title: Aspose.Slides for C++ API リファレンス
description: データ署名を確認します。
type: docs
weight: 222
url: /ja/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) メソッド


データ署名を確認します。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 受信データに対して計算されたハッシュ。 |
| str | const [String](../../../system/string/)\& | 使用されたハッシュアルゴリズムの名前。 |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 受信した署名。 |

### 戻り値

署名が有効な場合は true、そうでない場合は false。

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) メソッド


指定されたハッシュの署名が有効かどうかを検証します。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 署名されたデータのハッシュ値。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | パディングモード。署名が有効な場合は true、そうでない場合は false。 |

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [RSACryptoServiceProvider](../)
* クラス [RSASignaturePadding](../../rsasignaturepadding/)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)