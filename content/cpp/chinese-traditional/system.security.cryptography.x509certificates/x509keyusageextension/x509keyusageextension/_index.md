---
title: X509KeyUsageExtension()
second_title: Aspose.Slides for C++ API 參考文件
description: 預設建構子。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() 建構子

預設建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 金鑰用法的編碼資料。 |
| critical | **bool** | 關鍵性標誌。 |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) 建構子

建構子。

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | 金鑰用法。 |
| critical | **bool** | 關鍵性標誌。 |

## 另見

* 列舉 [X509KeyUsageFlags](../../x509keyusageflags/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [X509KeyUsageExtension](../)
* 類別 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* 函式庫 [Aspose.Slides](../../../)