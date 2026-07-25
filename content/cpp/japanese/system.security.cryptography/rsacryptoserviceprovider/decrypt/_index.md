---
title: Decrypt()
second_title: Aspose.Slides for C++ API リファレンス
description: メッセージを復号化します。未実装です。
type: docs
weight: 105
url: /ja/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr&, bool) メソッド

メッセージを復号化します。未実装です。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) を復号化します。 |
| use_oaep | **bool** | OAEP パディングを使用する場合は true、PKCS#1 v1.5 パディングを使用する場合は false。 |

### 戻り値

復号化データ配列。

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) メソッド

指定されたパディングモードを使用して入力データを復号化します。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 配列を復号化します。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | パディングモード。 |

### 戻り値

バイト配列形式の復号化データ。

## 参照

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RSACryptoServiceProvider](../)
* クラス [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)