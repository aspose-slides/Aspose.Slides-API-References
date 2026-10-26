---
title: Rectangle
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Representuje obdélníkovou oblast obrázku definovanou celočíselnými souřadnicemi X a Y levého horního rohu a její šířkou a výškou. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 235
url: /cs/system.drawing/rectangle/
---
## Rectangle třída

Represents a rectangular area of an image defined as integer X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) třídu to manage objects of this type.

```cpp
class Rectangle
```

## Metody

| Method | Description |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Vytvoří objekt [Rectangle](./) ze zadaného objektu [RectangleF](../rectanglef/) zaokrouhlením hodnot polohy a velikosti objektu [RectangleF](../rectanglef/) na následující vyšší celá čísla. |
| **bool** [Contains](./contains/)(int, int) const | Určuje, zda se zadaný bod nachází uvnitř obdélníku reprezentovaného aktuálním objektem. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Určuje, zda se zadaný bod nachází uvnitř obdélníku reprezentovaného aktuálním objektem. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Určuje, zda se zadaný obdélník nachází uvnitř obdélníku reprezentovaného aktuálním objektem. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Určuje, zda jsou obdélníky reprezentované aktuálním a zadaným objektem identické. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Vytvoří nový objekt [Rectangle](./), který představuje obdélník se zadanými polohami okrajů. |
| int [get_Bottom](./get_bottom/)() const | Vrací souřadnici y dolního okraje obdélníku reprezentovaného aktuálním objektem. |
| int [get_Height](./get_height/)() const | Vrací výšku obdélníku reprezentovaného aktuálním objektem. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Určuje, zda souřadnice X a Y levého horního rohu obdélníku reprezentovaného aktuálním objektem, stejně jako jeho šířka a výška, mají hodnotu 0. |
| int [get_Left](./get_left/)() const | Vrací souřadnici X levého okraje obdélníku reprezentovaného aktuálním objektem. |
| [Point](../point/) [get_Location](./get_location/)() const | Vrací instanci třídy [Point](../point/), která určuje polohu levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| int [get_Right](./get_right/)() const | Vrací souřadnici X pravého okraje obdélníku reprezentovaného aktuálním objektem. |
| [Size](../size/) [get_Size](./get_size/)() const | Vrací instanci třídy [Size](../size/), která určuje šířku a výšku obdélníku reprezentovaného aktuálním objektem. |
| int [get_Top](./get_top/)() const | Vrací souřadnici Y horního okraje obdélníku reprezentovaného aktuálním objektem. |
| int [get_Width](./get_width/)() const | Vrací šířku obdélníku reprezentovaného aktuálním objektem. |
| int [get_X](./get_x/)() const | Vrací souřadnici X levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| int [get_Y](./get_y/)() const | Vrací souřadnici Y levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód aktuálního objektu. |
| void [Inflate](./inflate/)(int, int) | Zvětší šířku a výšku obdélníku reprezentovaného aktuálním objektem při zachování polohy geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o zadané hodnoty. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Zvětší šířku a výšku obdélníku reprezentovaného aktuálním objektem při zachování polohy geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o hodnoty určené šířkou a výškou zadaného objektu velikosti. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Zvětší šířku a výšku obdélníku reprezentovaného zadaným objektem při zachování polohy geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o zadané hodnoty. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Nahradí obdélník reprezentovaný aktuálním objektem obdélníkem, který vznikne jeho průnikem s obdélníkem reprezentovaným zadaným objektem. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Vrací obdélník, který je výsledkem průniku zadaných obdélníků. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Určuje, zda se obdélníky reprezentované aktuálním a zadaným objektem překrývají. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Posune pozici obdélníku reprezentovaného aktuálním objektem o zadané hodnoty. |
| void [Offset](./offset/)(int, int) | Posune pozici obdélníku reprezentovaného aktuálním objektem o zadané hodnoty. |
|  [operator RectangleF](./operator_rectanglef/)() const | Vrací objekt [RectangleF](../rectanglef/), který představuje obdélník rovnocenný obdélníku reprezentovanému aktuálním objektem. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Vždy vrací true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vždy vrací false. |
|  [Rectangle](./rectangle/)() | Vytvoří novou instanci objektu [Rectangle](./), která představuje obdélník s hodnotami souřadnic X a Y a šířky a výšky nastavenými na 0. |
|  [Rectangle](./rectangle/)(int, int, int, int) | Vytvoří novou instanci objektu [Rectangle](./), která představuje obdélník se zadanými souřadnicemi levého horního rohu a šířkou a výškou. |
|  [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Vytvoří novou instanci objektu [Rectangle](./), která představuje obdélník, jehož souřadnice levého horního rohu jsou zadány jako instance třídy [Point](../point/) a jeho šířka a výška jako instance třídy [Size](../size/). |
|  [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Vytvoří novou instanci objektu [Rectangle](./), která představuje obdélník rovnocenný zadanému. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Vytvoří objekt [Rectangle](./) ze zadaného objektu [RectangleF](../rectanglef/) zaokrouhlením hodnot polohy a velikosti objektu [RectangleF](../rectanglef/) na nejbližší celá čísla. |
| void [set_Height](./set_height/)(int) | Nastavuje výšku obdélníku reprezentovaného aktuálním objektem. |
| void [set_Location](./set_location/)([Point](../point/)) | Nastavuje polohu levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| void [set_Size](./set_size/)([Size](../size/)) | Nastavuje šířku a výšku obdélníku reprezentovaného aktuálním objektem. |
| void [set_Width](./set_width/)(int) | Nastavuje šířku obdélníku reprezentovaného aktuálním objektem. |
| void [set_X](./set_x/)(int) | Nastavuje souřadnici X levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| void [set_Y](./set_y/)(int) | Nastavuje souřadnici Y levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| [String](../../system/string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci aktuálního objektu. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Vytvoří objekt [Rectangle](./) ze zadaného objektu [RectangleF](../rectanglef/) zkrácením hodnot polohy a velikosti objektu [RectangleF](../rectanglef/) na následující nižší celá čísla. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Vrací obdélník, který je výsledkem sjednocení zadaných obdélníků. |

## Pole

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Prázdný obdélník, tj. obdélník, jehož hodnoty polohy a velikosti jsou nulové. |

## Viz také

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)