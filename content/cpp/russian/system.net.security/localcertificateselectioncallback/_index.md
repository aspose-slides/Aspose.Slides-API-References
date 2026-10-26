---
title: LocalCertificateSelectionCallback
second_title: Aspose.Slides для C++ API Reference
description: Пользовательский делегат, используемый для выбора локального SSL-сертификата.
type: docs
weight: 79
url: /ru/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef

Пользовательский делегат, используемый для выбора локального SSL-сертификата.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## См. также

* Пространство имён [System::Net::Security](../)
* Библиотека [Aspose.Slides](../../)