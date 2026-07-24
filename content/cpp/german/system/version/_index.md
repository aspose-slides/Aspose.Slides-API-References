---
title: Version
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt eine Versionsnummer dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 1470
url: /de/system/version/
---
## Version Klasse

Stellt eine Versionsnummer dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
class Version
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Vergleicht die vom aktuellen Objekt und dem angegebenen Objekt dargestellten Versionen. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten Versionsnummern gleich sind. |
| int [get_Build](./get_build/)() const | Gibt die Build-Nummer zurück. |
| int [get_Major](./get_major/)() const | Gibt die Hauptversion zurück. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Gibt den hohen 16-bit Wert der Revisionsnummer zurück. |
| int [get_Minor](./get_minor/)() const | Gibt die Nebenversion zurück. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Gibt den niedrigen 16-bit Wert der Revisionsnummer zurück. |
| int [get_Revision](./get_revision/)() const | Gibt die Revisionsnummer zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die String-Darstellung einer Versionsnummer in eine äquivalente Instanz der Klasse [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | Gibt die String-Darstellung der vom aktuellen Objekt dargestellten Versionsnummer zurück. |
| [String](../string/) [ToString](./tostring/)(int) const | Gibt die String-Darstellung der angegebenen Anzahl von Abschnitten der vom aktuellen Objekt dargestellten Versionsnummer zurück. |
| [Version](./version/)(int, int, int, int) | Erstellt eine Instanz, die die angegebenen Haupt-, Neben-, Build- und Revisionswerte repräsentiert. |
| [Version](./version/)(int, int, int) | Erstellt eine Instanz, die die angegebenen Haupt-, Neben- und Build-Werte repräsentiert. |
| [Version](./version/)(int, int) | Erstellt eine Instanz, die die angegebenen Haupt- und Werte repräsentiert. |
| [Version](./version/)(const [String](../string/)\&) | Erstellt eine Instanz, die die als Zeichenkette dargestellte Versionsnummer repräsentiert. |
| [Version](./version/)() | Erstellt eine Instanz, die die Versionsnummer 0.0.-1.-1 repräsentiert. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)