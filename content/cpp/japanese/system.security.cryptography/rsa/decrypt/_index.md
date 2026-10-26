---
title: Decrypt()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパディングモードを使用して入力データを復号します。
type: docs
weight: 27
url: /ja/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) メソッド


指定されたパディングモードを使用して入力データを復号します。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 配列を復号します。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | パディングモード。 |

### 戻り値

バイト配列形式の復号済みデータ。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RSAEncryptionPadding](../../rsaencryptionpadding/)
* クラス [RSA](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)