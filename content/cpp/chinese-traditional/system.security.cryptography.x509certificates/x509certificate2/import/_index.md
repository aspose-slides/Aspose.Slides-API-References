---
title: Import()
second_title: Aspose.Slides for C++ API 參考文件
description: 從指定的憑證檔案匯入資訊。
type: docs
weight: 300
url: /zh-hant/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 方法

從指定的憑證檔案匯入資訊。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 憑證檔案名稱。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 存取憑證資料所需的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) 方法

從指定的憑證檔案匯入資訊。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 憑證檔案名稱。 |
| password | const [String](../../../system/string/)\& | 存取憑證資料所需的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 方法

從指定的憑證資料匯入資訊。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | X.509 憑證資料。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 存取憑證資料所需的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 方法

從指定的憑證資料匯入資訊。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 憑證檔案名稱。 |
| password | const [String](../../../system/string/)\& | 存取憑證資料所需的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) 方法

從指定的憑證檔案匯入資訊。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 憑證檔案名稱。 |

## X509Certificate2::Import(const ByteArrayPtr\&) 方法

從指定的憑證資料匯入資訊。

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 憑證檔案名稱。 |

## 另請參閱

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [X509Certificate2](../)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)