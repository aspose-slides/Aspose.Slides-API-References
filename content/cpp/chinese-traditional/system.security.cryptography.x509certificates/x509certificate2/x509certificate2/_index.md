---
title: X509Certificate2()
second_title: Aspose.Slides for C++ API 參考
description: 建立空的 X509Certificate2。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() 建構子

建立空的 [X509Certificate2](../)。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用於載入憑證的檔案。 |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | 一個 [X509Certificate](../../x509certificate/) 物件。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [String](../../../system/string/)\& | 憑證密碼。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 憑證密碼。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [String](../../../system/string/)\& | 憑證密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示金鑰儲存方式的旗標。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 憑證密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示金鑰儲存方式的旗標。 |

## X509Certificate2::X509Certificate2(const String\&, const String\&) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用於載入憑證的檔案。 |
| password | const [String](../../../system/string/)\& | 憑證密碼。 |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用於載入憑證的檔案。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 憑證密碼。 |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用於載入憑證的檔案。 |
| password | const [String](../../../system/string/)\& | 憑證密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示金鑰儲存方式的旗標。 |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 用於載入憑證的檔案。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 憑證密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示金鑰儲存方式的旗標。 |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證（公開部分）的位元組序列。 |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示私鑰的位元組序列。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示金鑰儲存方式的旗標。 |

## 參見

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)