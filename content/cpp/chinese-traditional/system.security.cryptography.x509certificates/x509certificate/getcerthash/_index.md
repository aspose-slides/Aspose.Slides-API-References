---
title: GetCertHash()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得目前物件的雜湊值，以位元組陣列形式。
type: docs
weight: 79
url: /zh-hant/system.security.cryptography.x509certificates/x509certificate/getcerthash/
---
## X509Certificate::GetCertHash() const method

取得目前物件的雜湊值，以位元組陣列形式。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash() const
```

### 傳回值

雜湊值。

## X509Certificate::GetCertHash(const HashAlgorithmName\&) const method

取得目前物件的雜湊值，以位元組陣列形式。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::GetCertHash(const HashAlgorithmName &hash_algorithm) const
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| hash_algorithm | const [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)\& | 雜湊演算法名稱。 |

### 傳回值

雜湊值。

## 另請參閱

* 型別別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [X509Certificate](../)
* 結構 [HashAlgorithmName](../../../system.security.cryptography/hashalgorithmname/)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* 函式庫 [Aspose.Slides](../../../)