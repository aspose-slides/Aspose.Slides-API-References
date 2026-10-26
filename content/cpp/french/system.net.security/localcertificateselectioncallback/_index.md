---
title: LocalCertificateSelectionCallback
second_title: Référence de l'API Aspose.Slides pour C++
description: Un délégué utilisateur utilisé pour sélectionner le certificat SSL local.
type: docs
weight: 79
url: /fr/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef


Un délégué utilisateur utilisé pour sélectionner le certificat SSL local.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## Voir aussi

* Espace de noms [System::Net::Security](../)
* Bibliothèque [Aspose.Slides](../../)