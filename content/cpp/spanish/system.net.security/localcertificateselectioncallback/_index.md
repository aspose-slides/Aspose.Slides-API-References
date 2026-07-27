---
title: LocalCertificateSelectionCallback
second_title: Referencia de la API de Aspose.Slides para C++
description: Un delegado de usuario utilizado para seleccionar un certificado SSL local.
type: docs
weight: 79
url: /es/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef


Un delegado de usuario utilizado para seleccionar un certificado SSL local.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## Ver también

* Espacio de nombres [System::Net::Security](../)
* Biblioteca [Aspose.Slides](../../)