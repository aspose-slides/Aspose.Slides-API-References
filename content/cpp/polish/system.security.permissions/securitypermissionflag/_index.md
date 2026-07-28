---
title: SecurityPermissionFlag
second_title: Odwołanie API Aspose.Slides dla C++
description: Flagi uprawnień bezpieczeństwa.
type: docs
weight: 27
url: /pl/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Flagi uprawnień zabezpieczeń.

```cpp
enum class SecurityPermissionFlag
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| NoFlags | 0 | Brak dostępu. |
| Assertion | 1 | Załóż, że uprawnienie jest przyznane. |
| UnmanagedCode | 2 | Wywołaj kod niezarządzany. |
| SkipVerification | 4 | Pomiń weryfikację kodu. |
| Execution | 8 | Wykonaj kod. |
| ControlThread | 16 | Wykonuj operacje na wątkach. |
| ControlEvidence | 32 | Kontroluj lub zmień dowody CLR. |
| ControlPolicy | 64 | Wyświetlaj i zmieniaj zasady. |
| SerializationFormatter | 128 | Serializuj. |
| ControlDomainPolicy | 256 | Ustaw zasady domeny. |
| ControlPrincipal | 512 | Kontroluj obiekt główny. |
| ControlAppDomain | 1024 | Kontroluj domenę aplikacji. |
| RemotingConfiguration | 2048 | Konfiguruj zdalne wywołania. |
| Infrastructure | 4096 | Podłącz się do infrastruktury CLR. |
| BindingRedirects | 8192 | Wykonaj jawne przekierowanie wiązania. |
| AllFlags | 16383 | Bez ograniczeń. |

## Zobacz także

* Przestrzeń nazw [System::Security::Permissions](../)
* Biblioteka [Aspose.Slides](../../)