---
title: VerifyHash()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたハッシュの署名が有効であることを検証します。
type: docs
weight: 170
url: /ja/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) メソッド

指定されたハッシュの署名が有効であることを検証します。

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 署名されたデータのハッシュ値。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 署名データ。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | ハッシュアルゴリズム。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | パディングモード。署名が有効な場合は true を返し、そうでない場合は false を返します。 |

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RSASignaturePadding](../../rsasignaturepadding/)
* クラス [RSA](../)
* 構造体 [HashAlgorithmName](../../hashalgorithmname/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)