---
title: OperatingSystem
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett specifikt operativsystem och tillhandahåller information om det. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Paketera alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1171
url: /sv/system/operatingsystem/
---
## OperatingSystem klass


Representerar ett specifikt operativsystem och tillhandahåller information om det. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Paketera alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class OperatingSystem
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Returnerar plattformsidentifieraren för operativsystemet som representeras av det aktuella objektet. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Returnerar namnet på service pack för operativsystemet som representeras av det aktuella objektet. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Returnerar en konstant referens till ett [Version](../version/)-objekt som representerar versionen av operativsystemet som representeras av det aktuella objektet. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Returnerar strängrepresentationen av versionen av operativsystemet som representeras av det aktuella objektet. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Indikerar om den aktuella applikationen körs på FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Indikerar om den aktuella applikationen körs på Linux. |
| static **bool** [IsMacOS](./ismacos/)() | Indikerar om den aktuella applikationen körs på MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Indikerar om den aktuella applikationen körs på den angivna plattformen. |
| static **bool** [IsWindows](./iswindows/)() | Indikerar om den aktuella applikationen körs på [Windows](../../system.windows/). |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Skapar en instans som representerar ett operativsystem specificerat som ett särskilt plattforms-ID och version. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Skapar en instans som representerar ett operativsystem specificerat som ett särskilt plattforms-ID, version och service pack. |
| [String](../string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av versionen av operativsystemet som representeras av det aktuella objektet. |
## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)