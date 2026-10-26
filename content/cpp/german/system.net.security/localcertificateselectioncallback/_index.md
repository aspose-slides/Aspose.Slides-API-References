---
title: LocalCertificateSelectionCallback
second_title: Aspose.Slides für C++ API Referenz
description: Ein vom Benutzer bereitgestellter Delegat, der zum Auswählen des lokalen SSL-Zertifikats verwendet wird.
type: docs
weight: 79
url: /de/system.net.security/localcertificateselectioncallback/
---
## LocalCertificateSelectionCallback typedef

Ein vom Benutzer bereitgestellter Delegat, der zum Auswählen des lokalen SSL-Zertifikats verwendet wird.

```cpp
using System::Net::Security::LocalCertificateSelectionCallback = typedef System::MulticastDelegate<System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>( System::SharedPtr<Object>, String, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection>, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate>, System::ArrayPtr<String>)>
```

## Siehe auch

* Namensraum [System::Net::Security](../)
* Bibliothek [Aspose.Slides](../../)