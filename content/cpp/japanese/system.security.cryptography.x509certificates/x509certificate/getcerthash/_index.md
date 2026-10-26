---
title: GetCertHash()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトのハッシュをバイト配列として取得します。
type: docs
weight: 79
url: /ja/system.security.cryptography.x509certificates/x509certificate/getcerthash/
---
## X509Certificate::GetCertHash() const メソッド


現在のオブジェクトのハッシュをバイト配列として取得します。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash() const
```


### 戻り値

ハッシュ値。

## X509Certificate::GetCertHash(const HashAlgorithmName\&) const メソッド


現在のオブジェクトのハッシュをバイト配列として取得します。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash(const HashAlgorithmName &hash_algorithm) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | ハッシュアルゴリズム名。 |

### 戻り値

ハッシュ値。

## 参照

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [X509Certificate](../)
* 構造体 [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)