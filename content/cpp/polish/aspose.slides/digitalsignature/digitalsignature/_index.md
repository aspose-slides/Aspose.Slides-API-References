---
title: DigitalSignature()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy nowy obiekt DigitalSignature z określonym certyfikatem.
type: docs
weight: 66
url: /pl/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) konstruktor

Tworzy nowy obiekt [DigitalSignature](../) z określonym certyfikatem.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certyfikat, który zostanie użyty do podpisania prezentacji. |

## DigitalSignature::DigitalSignature(System::String, System::String) konstruktor

Tworzy nowy obiekt [DigitalSignature](../) z określoną ścieżką do pliku certyfikatu i hasłem.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Ścieżka do pliku z certyfikatem. |
| password | [System::String](../../../system/string/) | Hasło wymagane do uzyskania dostępu do certyfikatu. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Klasa [DigitalSignature](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)