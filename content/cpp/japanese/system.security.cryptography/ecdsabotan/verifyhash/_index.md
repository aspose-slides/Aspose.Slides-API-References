---
title: VerifyHash()
second_title: Aspose.Slides for C++ API リファレンス
description: データ署名を検証します。
type: docs
weight: 183
url: /ja/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) メソッド

データ署名を検証します。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 受信データに対して計算されたハッシュ。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 受信した署名。 |

### 戻り値

署名が有効な場合は true、そうでない場合は false。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [ECDsaBotan](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)