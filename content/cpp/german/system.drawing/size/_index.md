---
title: Size
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt ein Paar von Ganzzahlwerten dar, die Breite und Höhe eines Bildes repräsentieren. Dieser Typ sollte auf dem Stack zugewiesen und Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 274
url: /de/system.drawing/size/
---
## Größenklasse

Stellt ein Paar von Ganzzahlwerten dar, die Breite und Höhe eines Bildes repräsentieren. Dieser Typ sollte auf dem Stack alloziert und Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../../system/smartptr/), um Objekte dieses Typs zu verwalten.

```cpp
class Size
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Gibt ein neues [Size](./)-Objekt zurück, das die Summe des angegebenen [Size](./)-Objekts darstellt, d. h. dessen Breitenwert gleich der Summe der Breitenwerte der angegebenen Objekte und dessen Höhenwert gleich der Summe der Höhenwerte der angegebenen Objekte ist. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Erstellt ein [Size](./)-Objekt aus dem angegebenen [SizeF](../sizef/)-Objekt, indem die Breiten- und Höhenwerte des [SizeF](../sizef/)-Objekts auf die nächsten höheren Ganzzahlwerte gerundet werden. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Bestimmt, ob das aktuelle Objekt und das angegebene Objekt gleich sind, d. h. dass sie dasselbe Paar von Breiten- und Höhenwerten darstellen. |
| int [get_Height](./get_height/)() const | Gibt den Höhenwert zurück, der vom aktuellen Objekt repräsentiert wird. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob sowohl Breiten- als auch Höhenwerte gleich 0 sind. |
| int [get_Width](./get_width/)() const | Gibt den Breitenwert zurück, der vom aktuellen Objekt repräsentiert wird. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
|  [operator Point](./operator_point/)() const | Erstellt eine Instanz des [Point](../point/)-Objekts und initialisiert seine X- und Y-Koordinaten mit den Breiten- bzw. Höhenwerten des aktuellen Objekts. |
|  [operator SizeF](./operator_sizef/)() const | Erstellt eine Instanz des [SizeF](../sizef/)-Objekts und initialisiert sie mit den Breiten- und Höhenwerten des aktuellen [Size](./)-Objekts. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Erstellt ein [Size](./)-Objekt aus dem angegebenen [SizeF](../sizef/)-Objekt, indem die Breiten- und Höhenwerte des [SizeF](../sizef/)-Objekts auf die nächstgelegenen Ganzzahlwerte gerundet werden. |
| void [set_Height](./set_height/)(int) | Setzt den Höhenwert, der vom aktuellen Objekt repräsentiert wird. |
| void [set_Width](./set_width/)(int) | Setzt den Breitenwert, der vom aktuellen Objekt repräsentiert wird. |
|  [Size](./size/)() | Erstellt ein neues [Size](./)-Objekt und initialisiert seine Breiten- und Höhenwerte mit 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Erstellt ein neues [Size](./)-Objekt und initialisiert seine Breiten- und Höhenwerte mit den X- und Y-Koordinaten des angegebenen Punktes. |
|  [Size](./size/)(int, int) | Erstellt ein neues [Size](./)-Objekt und initialisiert es mit dem angegebenen Wert. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Gibt ein neues [Size](./)-Objekt zurück, das das Ergebnis der Subtraktion von **size2** von **size1** darstellt, d. h. dessen Breitenwert das Ergebnis der Subtraktion des Breitenwerts von **size2** vom Breitenwert von **size1** ist und dessen Höhenwert das Ergebnis der Subtraktion des Höhenwerts von **size2** vom Höhenwert von **size1** ist. |
| [String](../../system/string/) [ToString](./tostring/)() const | Gibt die Zeichenkettendarstellung des Paars von Breiten- und Höhenwerten zurück, die vom aktuellen Objekt repräsentiert werden. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Erstellt ein [Size](./)-Objekt aus dem angegebenen [SizeF](../sizef/)-Objekt, indem die Breiten- und Höhenwerte des [SizeF](../sizef/)-Objekts auf die nächsten niedrigeren Ganzzahlwerte abgeschnitten werden. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Eine leere Instanz der Klasse [Size](./), deren Breiten- und Höhenwerte 0 sind. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)