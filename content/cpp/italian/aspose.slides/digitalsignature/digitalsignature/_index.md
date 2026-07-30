---
title: DigitalSignature()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto DigitalSignature con il certificato specificato.
type: docs
weight: 66
url: /it/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) costruttore

Crea un nuovo oggetto [DigitalSignature](../) con il certificato specificato.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certificato che verrà usato per firmare la presentazione. |

## DigitalSignature::DigitalSignature(System::String, System::String) costruttore

Crea un nuovo oggetto [DigitalSignature](../) con il percorso del file del certificato e la password specificati.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Percorso del file con il certificato. |
| password | [System::String](../../../system/string/) | Password necessaria per accedere al certificato. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [DigitalSignature](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)