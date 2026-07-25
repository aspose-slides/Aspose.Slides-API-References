---
title: Encrypt()
second_title: Aspose.Slides for C++ API リファレンス
description: メッセージを暗号化します。実装されていません。
type: docs
weight: 118
url: /ja/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) メソッド


メッセージを暗号化します。実装されていません。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) を暗号化する。 |
| use_oaep | **bool** | OAEP パディングを使用する場合は true、PKCS#1 v1.5 パディングを使用する場合は false。 |

### 戻り値

暗号化されたデータ配列。

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) メソッド


指定されたパディングモードを使用して入力データを暗号化します。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 配列を暗号化する。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | パディングモード。 |

### 戻り値

バイト配列形式の暗号化データ。

## 関連項目

* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [RSACryptoServiceProvider](../)
* クラス [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)