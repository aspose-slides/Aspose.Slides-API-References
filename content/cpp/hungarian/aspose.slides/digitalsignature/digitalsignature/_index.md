---
title: DigitalSignature()
second_title: Aspose.Slides C++ API Referencia
description: Létrehozza az új DigitalSignature objektumot a megadott tanúsítvánnyal.
type: docs
weight: 66
url: /hu/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) konstruktor

Létrehoz egy új [DigitalSignature](../) objektumot a megadott tanúsítvánnyal.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Tanúsítvány, amelyet a prezentáció aláírásához használnak. |

## DigitalSignature::DigitalSignature(System::String, System::String) konstruktor

Létrehoz egy új [DigitalSignature](../) objektumot a megadott tanúsítványfájl elérési útjával és jelszavával.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | A tanúsítványt tartalmazó fájl elérési útja. |
| password | [System::String](../../../system/string/) | A tanúsítvány eléréséhez szükséges jelszó. |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Osztály [DigitalSignature](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)