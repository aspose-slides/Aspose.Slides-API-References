---
title: PointF
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt ein Paar von Gleitkomma-X- und Y-Koordinaten in einfacher Genauigkeit eines Punktes in einer zweidimensionalen Ebene dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 222
url: /de/system.drawing/pointf/
---
## PointF Klasse

Stellt ein Paar von Gleitkomma-X- und Y-Koordinaten in einfacher Genauigkeit eines Punktes in einer zweidimensionalen Ebene dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class PointF
```

## Methoden

| Method | Description |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Fügt die Breiten- und Höhenwerte des angegebenen [SizeF](../sizef/) Objekts zu den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts hinzu. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Fügt die Breiten- und Höhenwerte des angegebenen [Size](../size/) Objekts zu den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts hinzu. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Bestimmt, ob das aktuelle Objekt und das angegebene Objekt gleich sind, d. h. dass sie dasselbe Paar von X- und Y-Koordinatenwerten darstellen. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob sowohl die X- als auch die Y-Koordinatenwerte gleich 0 sind. |
| **float** [get_X](./get_x/)() const | Gibt den von dem aktuellen Objekt dargestellten X-Koordinatenwert zurück. |
| **float** [get_Y](./get_y/)() const | Gibt den von dem aktuellen Objekt dargestellten Y-Koordinatenwert zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
| **bool** [IsNull](./isnull/)() const | Gibt immer false zurück. |
| explicit  [operator bool](./operator_bool/)() | Gibt immer true zurück. |
| [PointF](./pointf/)() | Konstruiert ein neues [PointF](./) Objekt und initialisiert dessen X- und Y-Koordinatenwerte mit 0. |
| [PointF](./pointf/)(**float**, **float**) | Konstruiert ein neues [PointF](./) Objekt und initialisiert es mit den angegebenen Werten. |
| [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Konstruiert ein neues [PointF](./) Objekt und initialisiert dessen X- und Y-Koordinatenwerte mit den Breiten- und Höhenwerten des angegebenen [SizeF](../sizef/) Objekts entsprechend. |
| void [set_X](./set_x/)(**float**) | Setzt den Wert der vom aktuellen Objekt dargestellten X-Koordinate. |
| void [set_Y](./set_y/)(**float**) | Setzt den Wert der vom aktuellen Objekt dargestellten Y-Koordinate. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Subtrahiert die Breiten- und Höhenwerte des angegebenen [SizeF](../sizef/) Objekts von den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Subtrahiert die Breiten- und Höhenwerte des angegebenen [Size](../size/) Objekts von den X- und Y-Koordinatenwerten des angegebenen [PointF](./) Objekts. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation des Paars von X- und Y-Koordinatenwerten zurück, die vom aktuellen Objekt dargestellt werden. |

## Felder

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Eine leere Instanz der [PointF](./) Klasse, deren X- und Y-Koordinatenwerte 0 sind. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)