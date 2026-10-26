---
title: X509Certificate()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 1
url: /zh-hant/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) 建構函式




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |

## X509Certificate::X509Certificate(const String\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 載入憑證的檔案。 |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | 用於初始化此物件的憑證。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [String](../../../system/string/)\& | 用於存取憑證資料的密碼。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用於存取憑證資料的密碼。 |

## X509Certificate::X509Certificate(const String\&, const String\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 載入憑證的檔案。 |
| password | const [String](../../../system/string/)\& | 用於存取憑證資料的密碼。 |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 載入憑證的檔案。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用於存取憑證資料的密碼。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [String](../../../system/string/)\& | 用於存取憑證資料的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何儲存金鑰的旗標。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證的位元組序列。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用於存取憑證資料的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何儲存金鑰的旗標。 |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 載入憑證的檔案。 |
| password | const [String](../../../system/string/)\& | 用於存取憑證資料的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何儲存金鑰的旗標。 |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 載入憑證的檔案。 |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | 用於存取憑證資料的密碼。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何儲存金鑰的旗標。 |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) 建構函式


建構函式。

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示已編碼憑證（公用部分）的位元組序列。 |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 表示私密金鑰的位元組序列。 |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | 指示如何儲存金鑰的旗標。 |

## 參見

* 列舉 [X509KeyStorageFlags](../../x509keystorageflags/)
* 型別定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [SecureStringPtr](../../../system.security/securestringptr/)
* 類別 [X509Certificate](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* 函式庫 [Aspose.Slides](../../../)