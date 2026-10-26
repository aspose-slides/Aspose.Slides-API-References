---
title: SecurityPermissionFlag
second_title: Aspose.Slides C++ API-referencia
description: Biztonsági engedély zászlói.
type: docs
weight: 27
url: /hu/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enumeráció


A biztonsági engedély zászlói.

```cpp
enum class SecurityPermissionFlag
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| NoFlags | 0 | Nincs hozzáférés. |
| Assertion | 1 | Állapítsa meg, hogy az engedély meg van adva. |
| UnmanagedCode | 2 | Nem kezelt kód meghívása. |
| SkipVerification | 4 | Kód ellenőrzésének kihagyása. |
| Execution | 8 | Kód végrehajtása. |
| ControlThread | 16 | Műveletek végrehajtása szálakon. |
| ControlEvidence | 32 | A CLR bizonyítékának vezérlése vagy módosítása. |
| ControlPolicy | 64 | Politika megtekintése és módosítása. |
| SerializationFormatter | 128 | Sorozatba alakítás. |
| ControlDomainPolicy | 256 | Domain politika beállítása. |
| ControlPrincipal | 512 | Fő objektum vezérlése. |
| ControlAppDomain | 1024 | Alkalmazásdomain vezérlése. |
| RemotingConfiguration | 2048 | Távoli hívások konfigurálása. |
| Infrastructure | 4096 | Csatlakozás a CLR infrastruktúrához. |
| BindingRedirects | 8192 | Kifejezett kötésirányítás végrehajtása. |
| AllFlags | 16383 | Korlátlan. |

## Lásd még

* Névtér [System::Security::Permissions](../)
* Könyvtár [Aspose.Slides](../../)