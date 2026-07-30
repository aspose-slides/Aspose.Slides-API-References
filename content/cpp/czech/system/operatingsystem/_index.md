---
title: OperatingSystem
second_title: Aspose.Slides pro referenci API C++
description: "Reprezentuje konkrétní operační systém a poskytuje o něm informace. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením tvrzení. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 1171
url: /cs/system/operatingsystem/
---
## OperatingSystem třída

Reprezentuje konkrétní operační systém a poskytuje o něm informace. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením tvrzení. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class OperatingSystem
```

## Metody

| Metoda | Popis |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Vrací identifikátor platformy operačního systému reprezentovaného aktuálním objektem. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Vrací název service packu operačního systému reprezentovaného aktuálním objektem. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Vrací konstantní referenci na objekt [Version](../version/) reprezentující verzi operačního systému reprezentovaného aktuálním objektem. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Vrací řetězcovou reprezentaci verze operačního systému reprezentovaného aktuálním objektem. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Určuje, zda aktuální aplikace běží na FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | Určuje, zda aktuální aplikace běží na Linuxu. |
| static **bool** [IsMacOS](./ismacos/)() | Určuje, zda aktuální aplikace běží na MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Určuje, zda aktuální aplikace běží na zadané platformě. |
| static **bool** [IsWindows](./iswindows/)() | Určuje, zda aktuální aplikace běží na [Windows](../../system.windows/). |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Vytvoří instanci, která reprezentuje operační systém specifikovaný jako konkrétní ID platformy a verze. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Vytvoří instanci, která reprezentuje operační systém specifikovaný jako konkrétní ID platformy, verze a service pack. |
| [String](../string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci verze operačního systému reprezentovaného aktuálním objektem. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)