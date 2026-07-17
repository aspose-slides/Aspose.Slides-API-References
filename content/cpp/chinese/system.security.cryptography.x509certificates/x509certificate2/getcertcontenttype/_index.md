---
title: GetCertContentType()
second_title: Aspose.Slides C++ API 参考
description: 获取指定字节数组中包含的证书类型。
type: docs
weight: 391
url: /zh/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) 方法

获取指定字节数组中包含的证书类型。

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 证书数据。 |

### 返回值

X.509 证书的类型。

## X509Certificate2::GetCertContentType(const String\&) 方法

获取指定文件中包含的证书类型。

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 证书文件名。 |

### 返回值

X.509 证书的类型。

## 另见

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)