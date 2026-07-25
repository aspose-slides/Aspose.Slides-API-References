---
title: Import()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された証明書ファイルから情報をインポートします。
type: docs
weight: 300
url: /ja/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) メソッド


指定された証明書ファイルから情報をインポートします。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書ファイル名。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書データにアクセスするために必要なパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) メソッド


指定された証明書ファイルから情報をインポートします。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書ファイル名。 |
| password | const [String](../../../system/string/)\& | 証明書データにアクセスするために必要なパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) メソッド


指定された証明書データから情報をインポートします。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | X.509証明書データ。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書データにアクセスするために必要なパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) メソッド


指定された証明書データから情報をインポートします。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 証明書ファイル名。 |
| password | const [String](../../../system/string/)\& | 証明書データにアクセスするために必要なパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) メソッド


指定された証明書ファイルから情報をインポートします。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書ファイル名。 |

## X509Certificate2::Import(const ByteArrayPtr\&) メソッド


指定された証明書データから情報をインポートします。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 証明書ファイル名。 |

## 参照

* 列挙体 [X509KeyStorageFlags](../../x509keystorageflags/)
* 型定義 [SecureStringPtr](../../../system.security/securestringptr/)
* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* クラス [String](../../../system/string/)
* クラス [X509Certificate2](../)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)