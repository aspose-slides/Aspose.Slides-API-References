---
title: GetCertContentType()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定位元組陣列中所包含之憑證類型。
type: docs
weight: 391
url: /zh-hant/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) 方法

取得指定位元組陣列中包含之憑證的類型。

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 憑證資料。 |

### 傳回值

X.509 憑證的類型。

## X509Certificate2::GetCertContentType(const String\&) 方法

取得指定檔案中包含之憑證的類型。

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 憑證檔案名稱。 |

### 傳回值

X.509 憑證的類型。

## 另請參閱

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [X509Certificate2](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)