---
title: VerifyHash()
second_title: Aspose.Slides for C++ API リファレンス
description: データ署名を検証します。
type: docs
weight: 222
url: /ja/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) メソッド

データ署名を検証します。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 受信データに対して計算されたハッシュ。 |
| str | const [String](../../../system/string/)\& | 使用されたハッシュアルゴリズムの名前。 |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 受信された署名。 |

### 戻り値

署名が有効な場合は true、そうでない場合は false。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [String](../../../system/string/)
* クラス [DSACryptoServiceProvider](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)