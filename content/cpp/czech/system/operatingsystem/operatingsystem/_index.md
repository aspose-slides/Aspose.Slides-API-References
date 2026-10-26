---
title: OperatingSystem()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří instanci, která představuje operační systém specifikovaný konkrétním identifikátorem platformy a verzí.
type: docs
weight: 1
url: /cs/system/operatingsystem/operatingsystem/
---
## OperatingSystem::OperatingSystem(PlatformID, const Version\&) konstruktor


Vytvoří instanci, která představuje operační systém specifikovaný konkrétním identifikátorem platformy a verzí.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | Identifikátor platformy operačního systému, který bude reprezentován vytvářeným objektem |
| version | const [Version](../../version/)\& | Verze operačního systému, který bude reprezentován vytvářeným objektem |

## OperatingSystem::OperatingSystem(PlatformID, const Version\&, const String\&) konstruktor


Vytvoří instanci, která představuje operační systém specifikovaný konkrétním identifikátorem platformy, verzí a servisním balíčkem.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version, const String &service_pack)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | Identifikátor platformy operačního systému, který bude reprezentován vytvářeným objektem |
| version | const [Version](../../version/)\& | Verze operačního systému, který bude reprezentován vytvářeným objektem |
| service_pack | const [String](../../string/)\& | Název servisního balíčku operačního systému, který bude reprezentován vytvářeným objektem |

## Viz také

* Enum [PlatformID](../../platformid/)
* Třída [Version](../../version/)
* Třída [OperatingSystem](../)
* Třída [String](../../string/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)