---
title: VerifySignature()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデータの DSA 署名を検証します。
type: docs
weight: 14
url: /ja/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) メソッド

指定されたデータの [DSA](../) 署名を検証します。

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) は **rgb_signature** で署名されます。 |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) 署名。 |

### 戻り値

true - **rgb_signature** が **rgb_hash** 上で計算された [DSA](../) 署名と一致する場合、そうでなければ false。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [DSA](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)