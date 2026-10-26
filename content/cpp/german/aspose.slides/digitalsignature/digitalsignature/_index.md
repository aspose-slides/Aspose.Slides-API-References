---
title: DigitalSignature()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues DigitalSignature-Objekt mit dem angegebenen Zertifikat.
type: docs
weight: 66
url: /de/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) Konstruktor

Erstellt ein neues [DigitalSignature](../)-Objekt mit dem angegebenen Zertifikat.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Zertifikat, das zum Signieren der Präsentation verwendet wird. |

## DigitalSignature::DigitalSignature(System::String, System::String) Konstruktor

Erstellt ein neues [DigitalSignature](../)-Objekt mit dem angegebenen Pfad zur Zertifikatsdatei und dem Kennwort.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Pfad zur Datei mit dem Zertifikat. |
| password | [System::String](../../../system/string/) | Passwort, das zum Zugriff auf das Zertifikat erforderlich ist. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Klasse [DigitalSignature](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)