---
title: VerifySignature()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデータのDSA署名を検証します。
type: docs
weight: 118
url: /ja/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) メソッド

指定されたデータの [DSA](../../dsa/) 署名を検証します。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) は **rgb_signature** で署名されました。 |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) 署名。 |

### 戻り値

true - **rgb_signature** が **rgb_hash** 上で計算された [DSA](../../dsa/) 署名と一致する場合、そうでなければ false。

## 参照

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [DSACryptoServiceProvider](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)