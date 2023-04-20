---
title: X509Certificate2()
second_title: Aspose.Slides for C++ API Reference
description: Constructs empty X509Certificate2.
type: docs
weight: 1
url: /cpp/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() constructor


Constructs empty [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | An [X509Certificate](../../x509certificate/) object. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [String](../../../system/string/)\& | Certificate password. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificate password. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [String](../../../system/string/)\& | Certificate password. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificate password. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [String](../../../system/string/)\& | Certificate password. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificate password. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [String](../../../system/string/)\& | Certificate password. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificate password. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate (public part). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents private key. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## See Also

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)