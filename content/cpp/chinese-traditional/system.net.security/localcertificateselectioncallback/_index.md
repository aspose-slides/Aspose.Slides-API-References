---
title: LocalCertificateSelectionCallback
second_title: Aspose.Slides for C++ API 參考
description: 用於選取本機 SSL 憑證的使用者委託。
type: docs
weight: 79
url: /zh-hant/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef

用於選取本機 SSL 憑證的使用者委託。

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## 參見

* 命名空間 [System::Net::Security](../)
* 函式庫 [Aspose.Slides](../../)