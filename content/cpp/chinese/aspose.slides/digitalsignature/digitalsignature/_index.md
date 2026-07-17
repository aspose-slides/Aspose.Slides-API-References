---
title: DigitalSignature()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的证书创建一个新的 DigitalSignature 对象。
type: docs
weight: 66
url: /zh/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) 构造函数

使用指定的证书创建一个新的 [DigitalSignature](../) 对象。

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | 将用于对演示文稿进行签名的证书。 |

## DigitalSignature::DigitalSignature(System::String, System::String) 构造函数

使用指定的证书文件路径和密码创建一个新的 [DigitalSignature](../) 对象。

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | 证书文件的路径。 |
| password | [System::String](../../../system/string/) | 访问证书所需的密码。 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [DigitalSignature](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)