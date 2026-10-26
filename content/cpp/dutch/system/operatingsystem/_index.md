---
title: OperatingSystem
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een specifiek besturingssysteem voor en biedt er informatie over. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 1171
url: /nl/system/operatingsystem/
---
## OperatingSystem klasse

Stelt een specifiek besturingssysteem voor en biedt informatie erover. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, want dat leidt tot runtime fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class OperatingSystem
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Retourneert de platformidentificatie van het besturingssysteem dat wordt vertegenwoordigd door het huidige object. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Retourneert de naam van het servicepack van het besturingssysteem dat wordt vertegenwoordigd door het huidige object. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Retourneert een constante referentie naar een [Version](../version/) object dat de versie van het besturingssysteem vertegenwoordigt dat wordt weergegeven door het huidige object. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Retourneert de tekenreeksrepresentatie van de versie van het besturingssysteem dat wordt vertegenwoordigd door het huidige object. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Geeft aan of de huidige applicatie draait op FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Geeft aan of de huidige applicatie draait op Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Geeft aan of de huidige applicatie draait op MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Geeft aan of de huidige applicatie draait op het opgegeven platform. |
| static **bool** [IsWindows](./iswindows/)() | Geeft aan of de huidige applicatie draait op [Windows](../../system.windows/). |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Construeert een instantie die een besturingssysteem vertegenwoordigt gespecificeerd als een bepaald platform-id en versie. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Construeert een instantie die een besturingssysteem vertegenwoordigt gespecificeerd als een bepaald platform-id, versie en servicepack. |
| [String](../string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van de versie van het besturingssysteem dat wordt vertegenwoordigd door het huidige object. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)