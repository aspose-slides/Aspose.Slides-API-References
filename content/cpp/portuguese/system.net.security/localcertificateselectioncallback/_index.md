---
title: LocalCertificateSelectionCallback
second_title: Referência da API Aspose.Slides para C++
description: Um delegado do usuário usado para selecionar o certificado SSL local.
type: docs
weight: 79
url: /pt/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef

Um delegado do usuário usado para selecionar o certificado SSL local.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## Veja Também

* Namespace [System::Net::Security](../)
* Biblioteca [Aspose.Slides](../../)