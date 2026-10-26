---
title: SignHash()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された入力値の署名を計算します。
type: docs
weight: 92
url: /ja/system.security.cryptography/ecdsa/signhash/
---
## ECDsa::SignHash(const ByteArrayPtr&) メソッド

指定された入力値の署名を計算します。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignHash(const ByteArrayPtr &hash)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hash | const [ByteArrayPtr](../../../system/bytearrayptr/)& | 署名対象データのハッシュ値。 |

### 戻り値

指定されたハッシュに対するECDSA署名。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [ECDsa](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)