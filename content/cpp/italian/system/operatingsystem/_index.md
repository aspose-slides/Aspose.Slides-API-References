---
title: OperatingSystem
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un particolare sistema operativo e fornisce informazioni al riguardo. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 1171
url: /it/system/operatingsystem/
---
## OperatingSystem classe

Rappresenta un particolare sistema operativo e fornisce informazioni al riguardo. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class OperatingSystem
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Restituisce l'identificatore della piattaforma del sistema operativo rappresentato dall'oggetto corrente. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Restituisce il nome del service pack del sistema operativo rappresentato dall'oggetto corrente. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Restituisce un riferimento costante a un oggetto [Version](../version/) che rappresenta la versione del sistema operativo rappresentato dall'oggetto corrente. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Restituisce la rappresentazione stringa della versione del sistema operativo rappresentato dall'oggetto corrente. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Indica se l'applicazione corrente è in esecuzione su FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Indica se l'applicazione corrente è in esecuzione su Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Indica se l'applicazione corrente è in esecuzione su MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Indica se l'applicazione corrente è in esecuzione sulla piattaforma specificata. |
| static **bool** [IsWindows](./iswindows/)() | Indica se l'applicazione corrente è in esecuzione su [Windows](../../system.windows/). |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Costruisce un'istanza che rappresenta un sistema operativo specificato come ID piattaforma particolare e versione. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Costruisce un'istanza che rappresenta un sistema operativo specificato come ID piattaforma particolare, versione e service pack. |
| [String](../string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa della versione del sistema operativo rappresentato dall'oggetto corrente. |

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)