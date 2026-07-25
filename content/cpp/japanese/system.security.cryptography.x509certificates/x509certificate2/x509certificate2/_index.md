---
title: X509Certificate2()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の X509Certificate2 を構築します。
type: docs
weight: 1
url: /ja/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() コンストラクタ


空の[X509Certificate2](../)を構築します。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | [X509Certificate](../../x509certificate/)オブジェクト。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイト列。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイト列。 |
| password | const [String](../../../system/string/)\& | 証明書のパスワード。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイト列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書のパスワード。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイト列。 |
| password | const [String](../../../system/string/)\& | 証明書のパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイト列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書のパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate2::X509Certificate2(const String\&, const String\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [String](../../../system/string/)\& | 証明書のパスワード。 |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書のパスワード。 |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [String](../../../system/string/)\& | 証明書のパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書のパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書（公開部）を表すバイト列。 |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | プライベートキーを表すバイト列。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## 参照

* 列挙型 [X509KeyStorageFlags](../../x509keystorageflags/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型定義 [SecureStringPtr](../../../system.security/securestringptr/)
* クラス [X509Certificate2](../)
* クラス [String](../../../system/string/)
* クラス [X509Certificate](../../x509certificate/)
* 名前空間 [System::Security::Cryptography::X509Certificates](../../)
* ライブラリ [Aspose.Slides](../../../)