---
title: Encrypt()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパディングモードを使用して入力データを暗号化します。
type: docs
weight: 53
url: /ja/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) メソッド

指定されたパディングモードを使用して入力データを暗号化します。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 配列を暗号化します。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | パディングモード。 |

### 戻り値

暗号化されたデータ（バイト配列形式）。

## 関連項目

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RSAEncryptionPadding](../../rsaencryptionpadding/)
* クラス [RSA](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)