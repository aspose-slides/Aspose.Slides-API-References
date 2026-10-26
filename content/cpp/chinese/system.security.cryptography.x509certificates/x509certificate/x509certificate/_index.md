---
title: X509Certificate()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 1
url: /zh/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) 构造函数




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |

## X509Certificate::X509Certificate(const String\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 要加载证书的文件。 |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | 用于初始化此对象的证书。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [String](../../../system/string/)\& | 用于访问证书数据的密码。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用于访问证书数据的密码。 |

## X509Certificate::X509Certificate(const String\&, const String\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 要加载证书的文件。 |
| password | const [String](../../../system/string/)\& | 用于访问证书数据的密码。 |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 要加载证书的文件。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用于访问证书数据的密码。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [String](../../../system/string/)\& | 用于访问证书数据的密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书的字节序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用于访问证书数据的密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 要加载证书的文件。 |
| password | const [String](../../../system/string/)\& | 用于访问证书数据的密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 要加载证书的文件。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用于访问证书数据的密码。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已编码证书（公钥部分）的字节序列。 |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示私钥的字节序列。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何存储密钥的标志。 |

## 另见

* 枚举 [X509KeyStorageFlags](../../x509keystorageflags/)
* 类型别名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类型别名 [SecureStringPtr](../../../system.security/securestringptr/)
* 类 [X509Certificate](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Security::Cryptography::X509Certificates](../../)
* 库 [Aspose.Slides](../../../)