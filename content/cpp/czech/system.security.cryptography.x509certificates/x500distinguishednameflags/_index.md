---
title: X500DistinguishedNameFlags
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Formátovací pravidla pro rozlišené jméno certifikátu X509.
type: docs
weight: 209
url: /cs/system.security.cryptography.x509certificates/x500distinguishednameflags/
---
## X500DistinguishedNameFlags enum

X509 certificate distinguished name formatting rules.

```cpp
enum class X500DistinguishedNameFlags
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Žádné zvláštní vlastnosti. |
| Reversed | 1 | Název je rezervován. |
| UseSemicolons | 16 | Použít středníky. |
| DoNotUsePlusSign | 32 | Název nepoužívá znak plus. |
| DoNotUseQuotes | 64 | Zakazuje uvozovky v názvu. |
| UseCommas | 128 | Umožňuje použití čárek. |
| UseNewLines | 256 | Umožňuje použití nových řádků. |
| UseUTF8Encoding | 4096 | Přepíná z používání Unicode na používání kódování UTF-8. |
| UseT61Encoding | 8192 | Přepíná na kódování T61. |
| ForceUTF8Encoding | 16384 | Vynutí používání UTF-8 při kódování konkrétních klíčů X500. |

## Viz také

* Jmenný prostor [System::Security::Cryptography::X509Certificates](../)
* Knihovna [Aspose.Slides](../../)