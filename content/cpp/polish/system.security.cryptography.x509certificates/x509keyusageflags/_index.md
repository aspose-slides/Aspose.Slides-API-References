---
title: X509KeyUsageFlags
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Definiuje, w jaki sposób klucz certyfikatu może być używany.
type: docs
weight: 274
url: /pl/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Definiuje, w jaki sposób klucz certyfikatu może być używany.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Brak parametrów użycia klucza. |
| EncipherOnly | 1 | Klucz może być używany wyłącznie do szyfrowania. |
| CrlSign | 2 | Klucz może być używany do podpisywania listy odwołań certyfikatów. |
| KeyCertSign | 4 | Klucz może być używany do podpisywania certyfikatów. |
| KeyAgreement | 8 | Klucz może być używany do uzgadniania klucza. |
| DataEncipherment | 16 | Klucz może być używany do szyfrowania danych. |
| KeyEncipherment | 32 | Klucz może być używany do szyfrowania klucza. |
| NonRepudiation | 64 | Klucz może być używany do uwierzytelniania. |
| DigitalSignature | 128 | Klucz może być używany jako podpis cyfrowy. |
| DecipherOnly | 32768 | Klucz może być używany wyłącznie do deszyfrowania. |

## Zobacz także

* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../)
* Biblioteka [Aspose.Slides](../../)