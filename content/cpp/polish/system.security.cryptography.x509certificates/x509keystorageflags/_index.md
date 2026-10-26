---
title: X509KeyStorageFlags
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, jak przechowywać klucz.
type: docs
weight: 261
url: /pl/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum

Określa, jak przechowywać klucz.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| DefaultKeySet | 0 | Użyj domyślnego zestawu kluczy. |
| UserKeySet | 1 | Użyj magazynu powiązanego z użytkownikiem zamiast lokalnego dla maszyny. |
| MachineKeySet | 2 | Użyj lokalnego magazynu maszyny zamiast użytkownika. |
| Exportable | 4 | Oznacza zaimportowane klucze jako eksportowalne. |
| UserProtected | 8 | Powiadom użytkownika, że klucz jest używany. |
| PersistKeySet | 16 | Klucz jest zachowywany podczas importowania certyfikatu. |

## Zobacz także

* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../)
* Biblioteka [Aspose.Slides](../../)