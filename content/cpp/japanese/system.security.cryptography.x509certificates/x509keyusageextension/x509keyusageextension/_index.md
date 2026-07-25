---
title: X509KeyUsageExtension()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトコンストラクタ。
type: docs
weight: 1
url: /ja/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() コンストラクタ

デフォルトコンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) コンストラクタ

コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | キー使用法のエンコードされたデータ。 |
| critical | **bool** | 重要度フラグ。 |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) コンストラクタ

コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | キー使用法。 |
| critical | **bool** | 重要度フラグ。 |

## 参照

* 列挙体 [X509KeyUsageFlags](../../x509keyusageflags/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [X509KeyUsageExtension](../)
* クラス [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)