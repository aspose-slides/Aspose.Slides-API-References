---
title: OperatingSystem
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt ein bestimmtes Betriebssystem dar und liefert Informationen darüber. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 1171
url: /de/system/operatingsystem/
---
## OperatingSystem Klasse


Stellt ein bestimmtes Betriebssystem dar und liefert Informationen darüber. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class OperatingSystem
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Gibt den Plattformidentifikator des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Gibt den Namen des Service Packs des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Gibt eine konstante Referenz auf ein [Version](../version/)-Objekt zurück, das die Version des vom aktuellen Objekt dargestellten Betriebssystems repräsentiert. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Gibt die Zeichenkettenrepräsentation der Version des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Gibt an, ob die aktuelle Anwendung auf FreeBSD läuft. |
| static **bool** [IsLinux](./islinux/)() | Gibt an, ob die aktuelle Anwendung auf Linux läuft. |
| static **bool** [IsMacOS](./ismacos/)() | Gibt an, ob die aktuelle Anwendung auf MacOS läuft. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Gibt an, ob die aktuelle Anwendung auf der angegebenen Plattform läuft. |
| static **bool** [IsWindows](./iswindows/)() | Gibt an, ob die aktuelle Anwendung auf [Windows](../../system.windows/) läuft. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Erstellt eine Instanz, die ein Betriebssystem darstellt, das durch eine bestimmte Plattform-ID und Version angegeben ist. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Erstellt eine Instanz, die ein Betriebssystem darstellt, das durch eine bestimmte Plattform-ID, Version und Service Pack angegeben ist. |
| [String](../string/) [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation der Version des vom aktuellen Objekt dargestellten Betriebssystems zurück. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)