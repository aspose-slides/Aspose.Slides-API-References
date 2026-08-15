---
title: GetNameInfo()
second_title: Aspose.Slides for C++ API 參考文件
description: 從憑證取得主體或發行者名稱。
type: docs
weight: 248
url: /zh-hant/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const 方法


取得憑證的主體或發行者名稱。

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | 名稱格式化選項。 |
| for_issuer | **bool** | 如果為 true，返回發行者名稱；否則返回主體名稱。 |

### 返回值

已格式化的發行者或主體名稱。

## 參見

* 列舉 [X509NameType](../../x509nametype/)
* 類別 [String](../../../system/string/)
* 類別 [X509Certificate2](../)
* 命名空間 [System::Security::Cryptography::X509Certificates](../../)
* 函式庫 [Aspose.Slides](../../../)