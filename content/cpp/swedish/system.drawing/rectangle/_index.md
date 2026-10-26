---
title: Rectangle
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett rektangulärt område i en bild som definieras av heltals-X- och Y-koordinater för dess övre vänstra hörn samt dess bredd och höjd. Denna typ bör allokeras på stacken och skickas till funktioner enligt värde eller referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ."
type: docs
weight: 235
url: /sv/system.drawing/rectangle/
---
## Rectangle klass

Representerar ett rektangulärt område i en bild definierat som heltals-X- och Y-koordinater för dess övre vänstra hörn samt dess bredd och höjd. Denna typ bör allokeras på stacken och skickas till funktioner enligt värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Rectangle
```

## Metoder

| Method | Description |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Skapar ett [Rectangle](./)-objekt från det angivna [RectangleF](../rectanglef/)-objektet genom att avrunda [RectangleF](../rectanglef/)-objektets positions- och storleksvärden till nästa högre heltalsvärden. |
| **bool** [Contains](./contains/)(int, int) const | Avgör om den angivna punkten ligger inom den rektangel som representeras av det aktuella objektet. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Avgör om den angivna punkten ligger inom den rektangel som representeras av det aktuella objektet. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Avgör om den angivna rektangeln ligger inom den rektangel som representeras av det aktuella objektet. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Avgör om rektanglarna som representeras av det aktuella och det angivna objektet är identiska. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Skapar ett nytt [Rectangle](./)-objekt som representerar en rektangel med de angivna kantpositionerna. |
| int [get_Bottom](./get_bottom/)() const | Returnerar y-koordinaten för rektangelns nedre kant som representeras av det aktuella objektet. |
| int [get_Height](./get_height/)() const | Returnerar höjden på rektangeln som representeras av det aktuella objektet. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Avgör om X- och Y-koordinaterna för det övre vänstra hörnet av den rektangel som representeras av det aktuella objektet samt dess bredd och höjd har värdet 0. |
| int [get_Left](./get_left/)() const | Returnerar X-koordinaten för rektangelns vänstra kant som representeras av det aktuella objektet. |
| [Point](../point/) [get_Location](./get_location/)() const | Returnerar en instans av [Point](../point/) klass som specificerar positionen för det övre vänstra hörnet av den rektangel som representeras av det aktuella objektet. |
| int [get_Right](./get_right/)() const | Returnerar X-koordinaten för rektangelns högra kant som representeras av det aktuella objektet. |
| [Size](../size/) [get_Size](./get_size/)() const | Returnerar en instans av [Size](../size/) klass som specificerar bredd och höjd för den rektangel som representeras av det aktuella objektet. |
| int [get_Top](./get_top/)() const | Returnerar Y-koordinaten för rektangelns övre kant som representeras av det aktuella objektet. |
| int [get_Width](./get_width/)() const | Returnerar bredden på rektangeln som representeras av det aktuella objektet. |
| int [get_X](./get_x/)() const | Returnerar X-koordinaten för det övre vänstra hörnet av den rektangel som representeras av det aktuella objektet. |
| int [get_Y](./get_y/)() const | Returnerar Y-koordinaten för det övre vänstra hörnet av den rektangel som representeras av det aktuella objektet. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hash-kod för det aktuella objektet. |
| void [Inflate](./inflate/)(int, int) | Ökar bredden och höjden på den rektangel som representeras av det aktuella objektet och behåller positionen för rektangelns geometriska centrum. Bredden och höjden ökas i båda riktningarna med de angivna mängderna. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Ökar bredden och höjden på den rektangel som representeras av det aktuella objektet, samtidigt som positionen för rektangelns geometriska centrum bibehålls. Bredden och höjden ökas i båda riktningarna med de mängder som motsvarar bredd- och höjdvärdena i det angivna storleksobjektet. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Ökar bredden och höjden på den rektangel som representeras av det angivna objektet, samtidigt som positionen för rektangelns geometriska centrum bibehålls. Bredden och höjden ökas i båda riktningarna med de angivna mängderna. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Ersätter den rektangel som representeras av det aktuella objektet med den rektangel som erhålls genom dess skärning med den rektangel som representeras av det angivna objektet. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Returnerar en rektangel som är resultatet av skärning av de angivna rektanglarna. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Avgör om rektanglarna som representeras av det aktuella och det angivna objektet skär varandra. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Förskjuter positionen för den rektangel som representeras av det aktuella objektet med de angivna värdena. |
| void [Offset](./offset/)(int, int) | Förskjuter positionen för den rektangel som representeras av det aktuella objektet med de angivna värdena. |
| [operator RectangleF](./operator_rectanglef/)() const | Returnerar ett [RectangleF](../rectanglef/)-objekt som representerar en rektangel ekvivalent med den rektangel som representeras av det aktuella objektet. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Returnerar alltid true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Returnerar alltid false. |
| [Rectangle](./rectangle/)() | Skapar en ny instans av [Rectangle](./)-objekt som representerar en rektangel med X- och Y-koordinater samt bredd- och höjdvärden satta till 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Skapar en ny instans av [Rectangle](./)-objekt som representerar en rektangel med de angivna koordinaterna för dess övre vänstra hörn samt bredd och höjd. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Skapar en ny instans av [Rectangle](./)-objekt som representerar en rektangel där koordinaterna för dess övre vänstra hörn anges som en instans av [Point](../point/) klass och dess bredd och höjd som en instans av [Size](../size/) klass. |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Skapar en ny instans av [Rectangle](./)-objekt som representerar den rektangel som är ekvivalent med den angivna. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Skapar ett [Rectangle](./)-objekt från det angivna [RectangleF](../rectanglef/)-objektet genom att avrunda [RectangleF](../rectanglef/)-objektets positions- och storleksvärden till närmaste heltal. |
| void [set_Height](./set_height/)(int) | Sätter höjden på den rektangel som representeras av det aktuella objektet. |
| void [set_Location](./set_location/)([Point](../point/)) | Sätter positionen för det övre vänstra hörnet av den rektangel som representeras av det aktuella objektet. |
| void [set_Size](./set_size/)([Size](../size/)) | Sätter bredden och höjden på den rektangel som representeras av det aktuella objektet. |
| void [set_Width](./set_width/)(int) | Sätter bredden på den rektangel som representeras av det aktuella objektet. |
| void [set_X](./set_x/)(int) | Sätter X-koordinaten för det övre vänstra hörnet av den rektangel som representeras av det aktuella objektet. |
| void [set_Y](./set_y/)(int) | Sätter Y-koordinaten för det övre vänstra hörnet av den rektangel som representeras av det aktuella objektet. |
| [String](../../system/string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av det aktuella objektet. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Skapar ett [Rectangle](./)-objekt från det angivna [RectangleF](../rectanglef/)-objektet genom att trunkera [RectangleF](../rectanglef/)-objektets positions- och storleksvärden till nästa lägre heltalsvärde. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Returnerar en rektangel som är resultatet av föreningen av de angivna rektanglarna. |

## Fält

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | En tom rektangel, dvs. en rektangel vars positions- och storleksvärden är noll. |

## Se också

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)