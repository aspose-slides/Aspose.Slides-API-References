---
title: X509Certificate()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 1
url: /system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) constructor




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |

## X509Certificate::X509Certificate(const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | A certificate used to initialize this object. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [String](../../../system/string/)\& | Password used to access the certificate data. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password used to access the certificate data. |

## X509Certificate::X509Certificate(const String\&, const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [String](../../../system/string/)\& | Password used to access the certificate data. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password used to access the certificate data. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [String](../../../system/string/)\& | Password used to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password used to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [String](../../../system/string/)\& | Password used to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | File to load certificate from. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Password used to access the certificate data. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents encoded certificate (public part). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequence of bytes that represents private key. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags indicating how to store key. |

## See Also

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)