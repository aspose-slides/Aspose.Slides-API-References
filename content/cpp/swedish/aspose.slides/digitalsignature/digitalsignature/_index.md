---
title: DigitalSignature()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt DigitalSignature-objekt med det angivna certifikatet.
type: docs
weight: 66
url: /sv/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) konstruktor

Skapar ett nytt [DigitalSignature](../)-objekt med det angivna certifikatet.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certifikat som kommer att användas för att signera presentationen. |

## DigitalSignature::DigitalSignature(System::String, System::String) konstruktor

Skapar ett nytt [DigitalSignature](../)-objekt med den angivna sökvägen till certifikatfilen och lösenordet.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Sökväg till filen med certifikatet. |
| password | [System::String](../../../system/string/) | Lösenord som krävs för att komma åt certifikatet. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Klass [DigitalSignature](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)