---
title: VerifyData()
second_title: Aspose.Slides for C++ API リファレンス
description: データの署名をチェックします。
type: docs
weight: 209
url: /ja/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) メソッド

データの署名をチェックします。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) を署名の確認に使用します。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 使用するハッシュアルゴリズム。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 受信した署名。 |

### 戻り値

署名が有効な場合は true、そうでない場合は false。

## 関連項目

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [RSACryptoServiceProvider](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)