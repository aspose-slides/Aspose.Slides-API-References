---
title: LocalCertificateSelectionCallback
second_title: Aspose.Slides for C++ API Reference
description: A user delegate used to select local SSL certificate.
type: docs
weight: 79
url: /system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef


A user delegate used to select local SSL certificate.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## See Also

* Namespace [System::Net::Security](../)
* Library [Aspose.Slides](../../)