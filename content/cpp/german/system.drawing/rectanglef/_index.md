---
title: RectangleF
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt einen rechteckigen Bereich eines Bildes dar, definiert durch ein-precisionelle Gleitkomma-X- und Y-Koordinaten seiner oberen linken Ecke sowie seiner Breite und Höhe. Dieser Typ sollte im Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 248
url: /de/system.drawing/rectanglef/
---
## RectangleF Klasse

Stellt einen rechteckigen Bereich eines Bildes dar, definiert durch ein-precisionelle Gleitkomma-X- und Y-Koordinaten seiner oberen linken Ecke sowie seiner Breite und Höhe. Dieser Typ sollte im Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class RectangleF
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Bestimmt, ob der angegebene Punkt innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Bestimmt, ob der angegebene Punkt innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Bestimmt, ob das angegebene Rechteck innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Bestimmt, ob die vom aktuellen und vom angegebenen Objekt dargestellten Rechtecke identisch sind. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Erstellt ein neues [RectangleF](./) Objekt, das ein Rechteck mit den angegebenen Kantenpositionen darstellt. |
| **float** [get_Bottom](./get_bottom/)() const | Gibt die Y-Koordinate der unteren Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| **float** [get_Height](./get_height/)() const | Gibt die Höhe des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob die X- und Y-Koordinaten der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks sowie dessen Breite und Höhe den Wert 0 haben. |
| **float** [get_Left](./get_left/)() const | Gibt die X-Koordinate der linken Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Gibt eine Instanz der [PointF](../pointf/) Klasse zurück, die die Position der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks angibt. |
| **float** [get_Right](./get_right/)() const | Gibt die X-Koordinate der rechten Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Gibt eine Instanz der [SizeF](../sizef/) Klasse zurück, die die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks angibt. |
| **float** [get_Top](./get_top/)() const | Gibt die Y-Koordinate der oberen Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| **float** [get_Width](./get_width/)() const | Gibt die Breite des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| **float** [get_X](./get_x/)() const | Gibt die X-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| **float** [get_Y](./get_y/)() const | Gibt die Y-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code des aktuellen Objekts zurück. |
| void [Inflate](./inflate/)(**float**, **float**) | Erhöht die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks und behält dabei die Position des geometrischen Zentrums des Rechtecks bei. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Erhöht die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks und behält dabei die Position des geometrischen Zentrums des Rechtecks bei. Breite und Höhe werden in beide Richtungen um die jeweiligen Breiten- und Höhenwerte des angegebenen Größenobjekts vergrößert. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Erhöht die Breite und Höhe des vom angegebenen Objekt dargestellten Rechtecks und behält dabei die Position des geometrischen Zentrums des Rechtecks bei. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Ersetzt das vom aktuellen Objekt dargestellte Rechteck durch das Rechteck, das aus der Schnittmenge mit dem vom angegebenen Objekt dargestellten Rechteck entsteht. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Gibt ein Rechteck zurück, das das Ergebnis der Schnittmenge der angegebenen Rechtecke ist. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Bestimmt, ob die vom aktuellen und vom angegebenen Objekt dargestellten Rechtecke sich schneiden. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Verschiebt die Position des vom aktuellen Objekt dargestellten Rechtecks um die angegebenen Werte. |
| void [Offset](./offset/)(**float**, **float**) | Verschiebt die Position des vom aktuellen Objekt dargestellten Rechtecks um die angegebenen Werte. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Gibt immer true zurück. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Gibt immer false zurück. |
| [RectangleF](./rectanglef/)() | Erstellt eine neue Instanz des [RectangleF](./) Objekts, das ein Rechteck mit X- und Y-Koordinaten sowie Breiten- und Höhenwerten von 0 darstellt. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Erstellt eine neue Instanz des [RectangleF](./) Objekts, das ein Rechteck mit den angegebenen Koordinaten seiner oberen linken Ecke sowie Breite und Höhe darstellt. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Erstellt eine neue Instanz des [RectangleF](./) Objekts, das ein Rechteck mit den Koordinaten seiner oberen linken Ecke, angegeben als Instanz der [PointF](../pointf/) Klasse, und seiner Breite und Höhe als Instanz der [SizeF](../sizef/) Klasse darstellt. |
| explicit [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Erstellt eine neue Instanz des [RectangleF](./) Objekts, das das dem angegebenen Rechteck entsprechende Rechteck darstellt. |
| void [set_Height](./set_height/)(**float**) | Setzt die Höhe des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Setzt die Position der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Setzt die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Width](./set_width/)(**float**) | Setzt die Breite des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_X](./set_x/)(**float**) | Setzt die X-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Y](./set_y/)(**float**) | Setzt die Y-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation des aktuellen Objekts zurück. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Gibt ein Rechteck zurück, das das Ergebnis der Vereinigung der angegebenen Rechtecke ist. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Ein leeres Rechteck, d.h. ein Rechteck, dessen Lage- und Größenwerte Null sind. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)