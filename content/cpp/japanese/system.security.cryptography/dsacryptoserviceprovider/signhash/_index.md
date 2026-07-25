---
title: SignHash()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された入力値の署名を計算します。
type: docs
weight: 196
url: /ja/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method


指定された入力値の署名を計算します。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 署名対象データのハッシュ値。 |
| str | const [String](../../../system/string/)\& | ハッシュを生成する際に使用されたハッシュアルゴリズムの識別子。 |

### 戻り値

[DSA](../../dsa/) 指定されたデータの署名。

## 関連項目

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [String](../../../system/string/)
* クラス [DSACryptoServiceProvider](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)