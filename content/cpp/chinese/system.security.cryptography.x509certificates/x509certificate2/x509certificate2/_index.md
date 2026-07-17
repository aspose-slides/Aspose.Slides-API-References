---
title: X509Certificate2()
second_title: Aspose.Slides for C++ API 参考
description: 构造空的 X509Certificate2。
type: docs
weight: 1
url: /zh/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() 构造函数


构造空的[X509Certificate2](../)。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用于加载证书的文件。 |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | 一个[X509Certificate](../../x509certificate/)对象。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [String](../../../system/string/)\& | 证书密码。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 证书密码。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [String](../../../system/string/)\& | 证书密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 证书密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate2::X509Certificate2(const String\&, const String\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用于加载证书的文件。 |
| password | const [String](../../../system/string/)\& | 证书密码。 |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用于加载证书的文件。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 证书密码。 |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用于加载证书的文件。 |
| password | const [String](../../../system/string/)\& | 证书密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用于加载证书的文件。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 证书密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书（公共部分）的字节序列。 |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示私钥的字节序列。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## 另见

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)