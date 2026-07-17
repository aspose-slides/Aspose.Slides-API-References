---
title: LocalCertificateSelectionCallback
second_title: Aspose.Slides C++ API 参考
description: 用于选择本地 SSL 证书的用户委托。
type: docs
weight: 79
url: /zh/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef

用于选择本地 SSL 证书的用户委托。

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## 另请参阅

* 命名空间 [System::Net::Security](../)
* 库 [Aspose.Slides](../../)