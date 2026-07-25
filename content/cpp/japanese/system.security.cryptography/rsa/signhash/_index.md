---
title: SignHash()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたハッシュ値の署名を計算します。
type: docs
weight: 144
url: /ja/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) メソッド


指定されたハッシュ値の署名を計算します。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | ハッシュ値。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | ハッシュアルゴリズム。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | パディングモード。指定されたハッシュに対して [RSA](../) 署名を返します。 |

## 参照

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)