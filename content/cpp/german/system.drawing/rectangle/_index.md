---
title: Rectangle
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen rechteckigen Bereich eines Bildes dar, der durch ganzzahlige X- und Y-Koordinaten seiner oberen linken Ecke sowie durch seine Breite und Höhe definiert ist. Dieser Typ sollte auf dem Stack zugewiesen und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 235
url: /de/system.drawing/rectangle/
---
## Rectangle Klasse

Stellt einen rechteckigen Bereich eines Bildes dar, der durch ganzzahlige X- und Y-Koordinaten seiner oberen linken Ecke sowie durch seine Breite und Höhe definiert ist. Dieser Typ sollte auf dem Stack zugewiesen und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../../system/smartptr/) zum Verwalten von Objekten dieses Typs.

```cpp
class Rectangle
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Erstellt ein [Rectangle](./)-Objekt aus dem angegebenen [RectangleF](../rectanglef/)-Objekt, indem die Lage- und Größenwerte des [RectangleF](../rectanglef/)-Objekts auf die nächsthöheren Ganzzahlen gerundet werden. |
| **bool** [Contains](./contains/)(int, int) const | Bestimmt, ob der angegebene Punkt innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Bestimmt, ob der angegebene Punkt innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Bestimmt, ob das angegebene Rechteck innerhalb des vom aktuellen Objekt dargestellten Rechtecks liegt. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Bestimmt, ob die vom aktuellen und dem angegebenen Objekt dargestellten Rechtecke identisch sind. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Erstellt ein neues [Rectangle](./)-Objekt, das ein Rechteck mit den angegebenen Kantenpositionen darstellt. |
| int [get_Bottom](./get_bottom/)() const | Gibt die y-Koordinate der unteren Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| int [get_Height](./get_height/)() const | Gibt die Höhe des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bestimmt, ob die X- und Y-Koordinaten der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks sowie seine Breite und Höhe den Wert 0 haben. |
| int [get_Left](./get_left/)() const | Gibt die X-Koordinate der linken Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [Point](../point/) [get_Location](./get_location/)() const | Gibt eine Instanz der Klasse [Point](../point/) zurück, die die Position der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks angibt. |
| int [get_Right](./get_right/)() const | Gibt die X-Koordinate der rechten Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| [Size](../size/) [get_Size](./get_size/)() const | Gibt eine Instanz der Klasse [Size](../size/) zurück, die die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks angibt. |
| int [get_Top](./get_top/)() const | Gibt die Y-Koordinate der oberen Kante des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| int [get_Width](./get_width/)() const | Gibt die Breite des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| int [get_X](./get_x/)() const | Gibt die X-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| int [get_Y](./get_y/)() const | Gibt die Y-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode des aktuellen Objekts zurück. |
| void [Inflate](./inflate/)(int, int) | Erhöht die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks, wobei die Position des geometrischen Zentrums des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Erhöht die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks, wobei die Position des geometrischen Zentrums des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die durch die Breiten- und Höhenwerte des angegebenen Größenobjekts festgelegten Beträge vergrößert. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Erhöht die Breite und Höhe des von dem angegebenen Objekt dargestellten Rechtecks, wobei die Position des geometrischen Zentrums des Rechtecks beibehalten wird. Breite und Höhe werden in beide Richtungen um die angegebenen Beträge vergrößert. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Ersetzt das vom aktuellen Objekt dargestellte Rechteck durch das Rechteck, das sich aus seiner Schnittmenge mit dem vom angegebenen Objekt dargestellten Rechteck ergibt. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Gibt ein Rechteck zurück, das das Ergebnis der Schnittmenge der angegebenen Rechtecke ist. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Bestimmt, ob die vom aktuellen und dem angegebenen Objekt dargestellten Rechtecke sich schneiden. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Verschiebt die Position des vom aktuellen Objekt dargestellten Rechtecks um die angegebenen Beträge. |
| void [Offset](./offset/)(int, int) | Verschiebt die Position des vom aktuellen Objekt dargestellten Rechtecks um die angegebenen Beträge. |
| [operator RectangleF](./operator_rectanglef/)() const | Gibt ein [RectangleF](../rectanglef/)-Objekt zurück, das ein dem vom aktuellen Objekt dargestellten Rechteck entsprechendes Rechteck darstellt. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Gibt immer true zurück. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Gibt immer false zurück. |
| [Rectangle](./rectangle/)() | Erstellt eine neue Instanz des [Rectangle](./)-Objekts, das ein Rechteck mit X- und Y-Koordinaten sowie Breiten- und Höhenwerten von 0 darstellt. |
| [Rectangle](./rectangle/)(int, int, int, int) | Erstellt eine neue Instanz des [Rectangle](./)-Objekts, das ein Rechteck mit den angegebenen Koordinaten seiner oberen linken Ecke sowie Breite und Höhe darstellt. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Erstellt eine neue Instanz des [Rectangle](./)-Objekts, das ein Rechteck mit den Koordinaten seiner oberen linken Ecke, angegeben als Instanz der Klasse [Point](../point/), und seiner Breite und Höhe, angegeben als Instanz der Klasse [Size](../size/), darstellt. |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Erstellt eine neue Instanz des [Rectangle](./)-Objekts, das das dem angegebenen Rechteck entsprechende Rechteck darstellt. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Erstellt ein [Rectangle](./)-Objekt aus dem angegebenen [RectangleF](../rectanglef/)-Objekt, indem die Lage- und Größenwerte des [RectangleF](../rectanglef/)-Objekts auf die nächsten Ganzzahlen gerundet werden. |
| void [set_Height](./set_height/)(int) | Setzt die Höhe des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Location](./set_location/)([Point](../point/)) | Setzt die Position der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Size](./set_size/)([Size](../size/)) | Setzt die Breite und Höhe des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Width](./set_width/)(int) | Setzt die Breite des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_X](./set_x/)(int) | Setzt die X-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| void [set_Y](./set_y/)(int) | Setzt die Y-Koordinate der oberen linken Ecke des vom aktuellen Objekt dargestellten Rechtecks. |
| [String](../../system/string/) [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation des aktuellen Objekts zurück. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Erstellt ein [Rectangle](./)-Objekt aus dem angegebenen [RectangleF](../rectanglef/)-Objekt, indem die Lage- und Größenwerte des [RectangleF](../rectanglef/)-Objekts auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Gibt ein Rechteck zurück, das das Ergebnis der Vereinigung der angegebenen Rechtecke ist. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Ein leeres Rechteck, d.h. ein Rechteck, dessen Lage- und Größenwerte den Wert Null haben. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)