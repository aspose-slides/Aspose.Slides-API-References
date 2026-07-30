---
title: SecurityPermissionFlag
second_title: Aspose.Slides pro C++ API Reference
description: Příznaky oprávnění zabezpečení.
type: docs
weight: 27
url: /cs/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag výčet

Příznaky oprávnění zabezpečení.

```cpp
enum class SecurityPermissionFlag
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| NoFlags | 0 | Žádný přístup. |
| Assertion | 1 | Potvrdit, že oprávnění je uděleno. |
| UnmanagedCode | 2 | Volat neřízený kód. |
| SkipVerification | 4 | Přeskočit ověřování kódu. |
| Execution | 8 | Spustit kód. |
| ControlThread | 16 | Provádět operace nad vlákny. |
| ControlEvidence | 32 | Řídit nebo měnit důkazy CLR. |
| ControlPolicy | 64 | Zobrazit a měnit politiku. |
| SerializationFormatter | 128 | Serializovat. |
| ControlDomainPolicy | 256 | Nastavit politiku domény. |
| ControlPrincipal | 512 | Řídit objekt principal. |
| ControlAppDomain | 1024 | Řídit aplikační doménu. |
| RemotingConfiguration | 2048 | Konfigurovat vzdálené volání. |
| Infrastructure | 4096 | Připojit se k infrastruktuře CLR. |
| BindingRedirects | 8192 | Provádět explicitní přesměrování vazeb. |
| AllFlags | 16383 | Neomezený. |

## Viz také

* jmenný prostor [System::Security::Permissions](../)
* Knihovna [Aspose.Slides](../../)