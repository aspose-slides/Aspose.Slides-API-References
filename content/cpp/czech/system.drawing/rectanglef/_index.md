---
title: RectangleF
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje obdélníkovou oblast obrázku definovanou jako souřadnice X a Y levého horního rohu s jednoduchou přesností a jeho šířkou a výškou. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k správě objektů tohoto typu."
type: docs
weight: 248
url: /cs/system.drawing/rectanglef/
---
## RectangleF třída


Reprezentuje obdélníkovou oblast obrázku definovanou souřadnicemi X a Y levého horního rohu s jednoduchou přesností a jeho šířkou a výškou. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../../system/smartptr/) k správě objektů tohoto typu.

```cpp
class RectangleF
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Určuje, zda je zadaný bod umístěn uvnitř obdélníku reprezentovaného aktuálním objektem. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Určuje, zda je zadaný bod umístěn uvnitř obdélníku reprezentovaného aktuálním objektem. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Určuje, zda je zadaný obdélník umístěn uvnitř obdélníku reprezentovaného aktuálním objektem. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Určuje, zda jsou obdélníky reprezentované aktuálním a zadaným objektem identické. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Vytvoří nový objekt [RectangleF](./), který reprezentuje obdélník se zadanými polohami hran. |
| **float** [get_Bottom](./get_bottom/)() const | Vrací souřadnici y spodní hrany obdélníku reprezentovaného aktuálním objektem. |
| **float** [get_Height](./get_height/)() const | Vrací výšku obdélníku reprezentovaného aktuálním objektem. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Určuje, zda mají souřadnice X a Y levého horního rohu obdélníku reprezentovaného aktuálním objektem, stejně jako jeho šířka a výška, hodnotu 0. |
| **float** [get_Left](./get_left/)() const | Vrací souřadnici X levé hrany obdélníku reprezentovaného aktuálním objektem. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Vrací instanci třídy [PointF](../pointf/), která určuje polohu levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| **float** [get_Right](./get_right/)() const | Vrací souřadnici X pravé hrany obdélníku reprezentovaného aktuálním objektem. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Vrací instanci třídy [SizeF](../sizef/), která určuje šířku a výšku obdélníku reprezentovaného aktuálním objektem. |
| **float** [get_Top](./get_top/)() const | Vrací souřadnici Y horní hrany obdélníku reprezentovaného aktuálním objektem. |
| **float** [get_Width](./get_width/)() const | Vrací šířku obdélníku reprezentovaného aktuálním objektem. |
| **float** [get_X](./get_x/)() const | Vrací souřadnici X levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| **float** [get_Y](./get_y/)() const | Vrací souřadnici Y levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód aktuálního objektu. |
| void [Inflate](./inflate/)(**float**, **float**) | Zvětší šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachová polohu geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o zadané hodnoty. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Zvětší šířku a výšku obdélníku reprezentovaného aktuálním objektem, přičemž zachová polohu geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o hodnoty šířky a výšky zadaného objektu velikosti. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Zvětší šířku a výšku obdélníku reprezentovaného zadaným objektem, přičemž zachová polohu geometrického středu obdélníku. Šířka a výška jsou zvětšeny v obou směrech o zadané hodnoty. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Nahradí obdélník reprezentovaný aktuálním objektem obdélníkem, který vznikne jejich průnikem s obdélníkem reprezentovaným zadaným objektem. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Vrací obdélník, který je výsledkem průniku zadaných obdélníků. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Určuje, zda se obdélníky reprezentované aktuálním a zadaným objektem překrývají. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Posune polohu obdélníku reprezentovaného aktuálním objektem o zadané hodnoty. |
| void [Offset](./offset/)(**float**, **float**) | Posune polohu obdélníku reprezentovaného aktuálním objektem o zadané hodnoty. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Vždy vrací true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vždy vrací false. |
|  [RectangleF](./rectanglef/)() | Vytvoří novou instanci objektu [RectangleF](./), který reprezentuje obdélník se souřadnicemi X a Y a hodnotami šířky a výšky nastavenými na 0. |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Vytvoří novou instanci objektu [RectangleF](./), který reprezentuje obdélník se zadanými souřadnicemi levého horního rohu a šířkou a výškou. |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Vytvoří novou instanci objektu [RectangleF](./), který reprezentuje obdélník, jehož souřadnice levého horního rohu jsou zadány jako instance třídy [PointF](../pointf/) a jeho šířka a výška jako instance třídy [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Vytvoří novou instanci objektu [RectangleF](./), který představuje obdélník ekvivalentní zadanému. |
| void [set_Height](./set_height/)(**float**) | Nastaví výšku obdélníku reprezentovaného aktuálním objektem. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Nastaví polohu levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Nastaví šířku a výšku obdélníku reprezentovaného aktuálním objektem. |
| void [set_Width](./set_width/)(**float**) | Nastaví šířku obdélníku reprezentovaného aktuálním objektem. |
| void [set_X](./set_x/)(**float**) | Nastaví souřadnici X levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| void [set_Y](./set_y/)(**float**) | Nastaví souřadnici Y levého horního rohu obdélníku reprezentovaného aktuálním objektem. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci aktuálního objektu. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Vrací obdélník, který je výsledkem sjednocení zadaných obdélníků. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | Prázdný obdélník, tj. obdélník, jehož souřadnice a rozměry mají nulové hodnoty. |

## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)