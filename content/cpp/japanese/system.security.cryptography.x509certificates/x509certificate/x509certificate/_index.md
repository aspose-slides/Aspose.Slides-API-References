---
title: X509Certificate()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 1
url: /ja/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) コンストラクタ




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイトシーケンス。 |

## X509Certificate::X509Certificate(const String\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | このオブジェクトを初期化するために使用される証明書。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイトシーケンス。 |
| password | const [String](../../../system/string/)\& | 証明書データにアクセスするために使用されるパスワード。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイトシーケンス。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書データにアクセスするために使用されるパスワード。 |

## X509Certificate::X509Certificate(const String\&, const String\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [String](../../../system/string/)\& | 証明書データにアクセスするために使用されるパスワード。 |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書データにアクセスするために使用されるパスワード。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイトシーケンス。 |
| password | const [String](../../../system/string/)\& | 証明書データにアクセスするために使用されるパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書を表すバイトシーケンス。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書データにアクセスするために使用されるパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [String](../../../system/string/)\& | 証明書データにアクセスするために使用されるパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 証明書を読み込むファイル。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 証明書データにアクセスするために使用されるパスワード。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) コンストラクタ


コンストラクタ。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | エンコードされた証明書（公開部）を表すバイトシーケンス。 |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | プライベートキーを表すバイトシーケンス。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | キーの保存方法を示すフラグ。 |

## 参照

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)