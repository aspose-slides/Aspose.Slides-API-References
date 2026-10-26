---
title: Point
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt ein Paar von ganzzahligen X- und Y-Koordinaten eines Punktes in einer zweidimensionalen Ebene dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 209
url: /de/system.drawing/point/
---
## Point Klasse

Stellt ein Paar von ganzzahligen X- und Y-Koordinaten eines Punktes in einer zweidimensionalen Ebene dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../../system/smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
class Point
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Addiert die Breiten- und Höhenwerte des angegebenen [Size](../size/)-Objekts zu den X- und Y-Koordinatenwerten des angegebenen [Point](./)-Objekts entsprechend. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Konstruiert ein [Point](./)-Objekt aus dem angegebenen [PointF](../pointf/)-Objekt, indem die X- und Y-Koordinatenwerte des [PointF](../pointf/)-Objekts auf die nächsthöheren Ganzzahlen gerundet werden. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Bestimmt, ob das aktuelle Objekt und das angegebene Objekt gleich sind, d.h. dass sie dasselbe Paar von X- und Y-Koordinatenwerten darstellen. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob sowohl X- als auch Y-Koordinatenwerte gleich 0 sind. |
| int [get_X](./get_x/)() const | Gibt den Wert der vom aktuellen Objekt dargestellten X-Koordinate zurück. |
| int [get_Y](./get_y/)() const | Gibt den Wert der vom aktuellen Objekt dargestellten Y-Koordinate zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
| size_t [getStdHash](./getstdhash/)() const | Gibt einen Hash-Wert für das aktuelle Objekt zurück. |
| **bool** [IsNull](./isnull/)() const | Gibt immer false zurück. |
| void [Offset](./offset/)(int, int) | Verschiebt den vom aktuellen Objekt dargestellten X- und Y-Koordinatenwert um die angegebenen Werte. |
| void [Offset](./offset/)([Point](./)) | Verschiebt die vom aktuellen Objekt dargestellten X- und Y-Koordinaten um die Werte der X- und Y-Koordinaten des angegebenen [Point](./)-Objekts entsprechend. |
| [operator PointF](./operator_pointf/)() const | Konstruiert eine Instanz des [PointF](../pointf/)-Objekts und initialisiert sie mit den X- und Y-Koordinatenwerten des aktuellen [Point](./)-Objekts. |
| [operator Size](./operator_size/)() const | Konstruiert eine Instanz des [Size](../size/)-Objekts und initialisiert seine Breiten- und Höhenwerte mit den vom aktuellen Objekt dargestellten X- und Y-Koordinatenwerten entsprechend. |
| [Point](./point/)() | Konstruiert ein neues [Point](./)-Objekt und initialisiert seine X- und Y-Koordinatenwerte mit 0. |
| [Point](./point/)(int, int) | Konstruiert ein neues [Point](./)-Objekt und initialisiert es mit den angegebenen Werten. |
| [Point](./point/)(const [Size](../size/)\&) | Konstruiert ein neues [Point](./)-Objekt und initialisiert seine X- und Y-Koordinatenwerte mit den Breiten- und Höhenwerten des angegebenen [SizeF](../sizef/)-Objekts entsprechend. |
| [Point](./point/)(int) | Konstruiert ein neues [Point](./)-Objekt und initialisiert seinen X-Koordinatenwert mit einem Wert, der aus den hohen 16 Bits der angegebenen 32-Bit-Ganzzahl gebildet wird, und seinen Y-Koordinatenwert mit einem Wert, der aus den niedrigen 16 Bits der angegebenen 32-Bit-Ganzzahl gebildet wird. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Konstruiert ein [Point](./)-Objekt aus dem angegebenen [PointF](../pointf/)-Objekt, indem die X- und Y-Koordinatenwerte des [PointF](../pointf/)-Objekts auf die nächstgelegenen Ganzzahlen gerundet werden. |
| void [set_X](./set_x/)(int) | Setzt den vom aktuellen Objekt dargestellten X-Koordinatenwert. |
| void [set_Y](./set_y/)(int) | Setzt den vom aktuellen Objekt dargestellten Y-Koordinatenwert. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Subtrahiert die Breiten- und Höhenwerte des angegebenen [Size](../size/)-Objekts von den X- und Y-Koordinatenwerten des angegebenen [Point](./)-Objekts entsprechend. |
| [String](../../system/string/) [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation des Paars von X- und Y-Koordinatenwerten zurück, das vom aktuellen Objekt dargestellt wird. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Konstruiert ein [Point](./)-Objekt aus dem angegebenen [PointF](../pointf/)-Objekt, indem die X- und Y-Koordinatenwerte des [PointF](../pointf/)-Objekts auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Eine leere Instanz der Klasse [Point](./), deren X- und Y-Koordinatenwerte 0 sind. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)