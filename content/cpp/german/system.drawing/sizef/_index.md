---
title: SizeF
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt ein Paar von Gleitkommawerten einfacher Genauigkeit dar, die Breite und Höhe eines Bildes repräsentieren. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 287
url: /de/system.drawing/sizef/
---
## SizeF Klasse

Stellt ein Paar von Gleitkommawerten einfacher Genauigkeit dar, die Breite und Höhe eines Bildes repräsentieren. Dieser Typ sollte auf dem Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class SizeF
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Gibt ein neues [SizeF](./) Objekt zurück, das die Summe der angegebenen [SizeF](./) Objekte ist, d.h. dessen Breitenwert gleich der Summe der Breitenwerte der angegebenen Objekte und dessen Höhenwert gleich der Summe der Höhenwerte der angegebenen Objekte ist. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Bestimmt, ob das aktuelle Objekt und das angegebene Objekt gleich sind, d.h. dass sie dasselbe Paar von Breiten- und hegiht-Werten repräsentieren. |
| **float** [get_Height](./get_height/)() const | Gibt den Höhenwert zurück, der vom aktuellen Objekt repräsentiert wird. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob sowohl Breiten- als auch hegiht-Werte gleich 0 sind. |
| **float** [get_Width](./get_width/)() const | Gibt den Breitenwert zurück, der vom aktuellen Objekt repräsentiert wird. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
|  [operator PointF](./operator_pointf/)() const | Konvertiert das aktuelle Objekt in eine Instanz des [Point](../point/) Objekts, indem seine X- und Y-Koordinate mit den Breiten- bzw. Höhenwerten des aktuellen Objekts initialisiert werden. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Fügt die Breiten- und Höhenwerte des angegebenen [SizeF](./) Objekts den Breiten- und Höhenwerten des aktuellen [SizeF](./) Objekts entsprechend hinzu. |
| void [set_Height](./set_height/)(**float**) | Setzt den Höhenwert, der vom aktuellen Objekt repräsentiert wird. |
| void [set_Width](./set_width/)(**float**) | Setzt den Breitenwert, der vom aktuellen Objekt repräsentiert wird. |
|  [SizeF](./sizef/)() | Erstellt ein neues [SizeF](./) Objekt und initialisiert seine Breiten- und Höhenwerte mit 0. |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Erstellt ein neues [SizeF](./) Objekt und initialisiert seine Breiten- und Höhenwerte mit den X- und Y-Koordinaten des angegebenen Punktes entsprechend. |
|  [SizeF](./sizef/)(**float**, **float**) | Erstellt ein neues [SizeF](./) Objekt und initialisiert es mit den angegebenen Werten. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Gibt ein neues [SizeF](./) Objekt zurück, das das Ergebnis der Subtraktion von **size2** von **size1** ist, d.h. dessen Breitenwert das Ergebnis der Subtraktion des Breitenwerts von **size2** von dem Breitenwert von **size1** und dessen Höhenwert das Ergebnis der Subtraktion des Höhenwerts von **size2** von dem Höhenwert von **size1** ist. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Konvertiert das aktuelle Objekt in eine Instanz des [Point](../point/) Objekts, indem seine X- und Y-Koordinate mit den Breiten- bzw. Höhenwerten des aktuellen Objekts initialisiert werden. |
| [Size](../size/) [ToSize](./tosize/)() const | Erstellt ein [Size](../size/) Objekt aus dem aktuellen [SizeF](./) Objekt, indem die Breiten- und Höhenwerte des [SizeF](./) Objekts auf die nächstniedrigeren Ganzzahlwerte abgeschnitten werden. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Gibt die String-Repräsentation des Paars von Breiten- und hegiht-Werten zurück, das vom aktuellen Objekt repräsentiert wird. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Eine leere Instanz der [SizeF](./) Klasse, deren Breiten- und Höhenwerte 0 sind. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)