---
title: X509KeyUsageFlags
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert hoe de certificaatsleutel kan worden gebruikt.
type: docs
weight: 274
url: /nl/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum


Definieert hoe de certificaatsleutel kan worden gebruikt.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Geen sleutelgebruikparameters. |
| EncipherOnly | 1 | Sleutel kan alleen voor versleuteling worden gebruikt. |
| CrlSign | 2 | Sleutel kan worden gebruikt om een certificaat intrekkingslijst te ondertekenen. |
| KeyCertSign | 4 | Sleutel kan worden gebruikt om certificaten te ondertekenen. |
| KeyAgreement | 8 | Sleutel kan worden gebruikt om een sleutelovereenkomst te bepalen. |
| DataEncipherment | 16 | Sleutel kan worden gebruikt voor gegevensversleuteling. |
| KeyEncipherment | 32 | Sleutel kan worden gebruikt voor sleutelversleuteling. |
| NonRepudiation | 64 | Sleutel kan worden gebruikt voor authenticatie. |
| DigitalSignature | 128 | Sleutel kan worden gebruikt als een digitale handtekening. |
| DecipherOnly | 32768 | Sleutel kan alleen voor ontsleuteling worden gebruikt. |

## Zie ook

* Naamruimte [System::Security::Cryptography::X509Certificates](../)
* Bibliotheek [Aspose.Slides](../../)