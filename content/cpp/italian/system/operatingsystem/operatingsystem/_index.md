---
title: OperatingSystem()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce un'istanza che rappresenta un sistema operativo specificato con un determinato ID piattaforma e versione.
type: docs
weight: 1
url: /it/system/operatingsystem/operatingsystem/
---
## OperatingSystem::OperatingSystem(PlatformID, const Version\&) costruttore

Crea un'istanza che rappresenta un sistema operativo specificato come ID piattaforma e versione particolari.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | L'identificatore della piattaforma del sistema operativo da rappresentare mediante l'oggetto in costruzione |
| version | const [Version](../../version/)\& | La versione del sistema operativo da rappresentare mediante l'oggetto in costruzione |

## OperatingSystem::OperatingSystem(PlatformID, const Version\&, const String\&) costruttore

Crea un'istanza che rappresenta un sistema operativo specificato con un determinato ID piattaforma, versione e pacchetto di aggiornamento.

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version, const String &service_pack)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | L'identificatore della piattaforma del sistema operativo da rappresentare mediante l'oggetto in costruzione |
| version | const [Version](../../version/)\& | La versione del sistema operativo da rappresentare mediante l'oggetto in costruzione |
| service_pack | const [String](../../string/)\& | Il nome del pacchetto di aggiornamento del sistema operativo da rappresentare mediante l'oggetto in costruzione |

## Vedi anche

* Enum [PlatformID](../../platformid/)
* Class [Version](../../version/)
* Class [OperatingSystem](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)