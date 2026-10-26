---
title: GetNameInfo()
second_title: Aspose.Slides C++ API 参考
description: 获取证书的主题或颁发者名称。
type: docs
weight: 248
url: /zh/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method

获取证书的主题或颁发者名称。

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | 名称格式化选项。 |
| for_issuer | **bool** | 若为 true，则返回颁发者名称；否则返回主题名称。 |

### 返回值

格式化的颁发者或主题名称。

## 另见

* 枚举 [X509NameType](../../x509nametype/)
* 类 [String](../../../system/string/)
* 类 [X509Certificate2](../)
* 命名空间 [System::Security::Cryptography::X509Certificates](../../)
* 库 [Aspose.Slides](../../../)