---
title: X509KeyUsageFlags
second_title: Aspose.Slides pro referenci API C++
description: Definuje, jak lze klíč certifikátu použít.
type: docs
weight: 274
url: /cs/system.security.cryptography.x509certificates/x509keyusageflags/
---
## Výčtový typ X509KeyUsageFlags

Definuje, jak lze klíč certifikátu použít.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Žádné parametry použití klíče. |
| EncipherOnly | 1 | Klíč může být použit pouze k šifrování. |
| CrlSign | 2 | Klíč může být použit k podepsání seznamu odvolaných certifikátů. |
| KeyCertSign | 4 | Klíč může být použit k podepsání certifikátů. |
| KeyAgreement | 8 | Klíč může být použit k určení dohody o klíči. |
| DataEncipherment | 16 | Klíč může být použit k šifrování dat. |
| KeyEncipherment | 32 | Klíč může být použit k šifrování klíče. |
| NonRepudiation | 64 | Klíč může být použit k ověření. |
| DigitalSignature | 128 | Klíč může být použit jako digitální podpis. |
| DecipherOnly | 32768 | Klíč může být použit pouze k dešifrování. |

## Viz také

* Jmenný prostor [System::Security::Cryptography::X509Certificates](../)
* Knihovna [Aspose.Slides](../../)