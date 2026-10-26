---
title: GetCertHashString()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトの SHA1 ハッシュを十六進文字列として取得します。
type: docs
weight: 92
url: /ja/system.security.cryptography.x509certificates/x509certificate/getcerthashstring/
---
## X509Certificate::GetCertHashString() const メソッド

現在のオブジェクトの [SHA1](../../../system.security.cryptography/sha1/) ハッシュを十六進文字列として取得します。

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString() const
```

### 戻り値

十六進文字列です。

## X509Certificate::GetCertHashString(const HashAlgorithmName\&) const メソッド

現在のオブジェクトの [SHA1](../../../system.security.cryptography/sha1/) ハッシュを十六進文字列として取得します。

```cpp
virtual String System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHashString(const HashAlgorithmName &hash_algorithm) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | ハッシュアルゴリズム名。 |

### 戻り値

十六進文字列です。

## 参照

* クラス [String](../../../system/string/)
* クラス [X509Certificate](../)
* 構造体 [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)