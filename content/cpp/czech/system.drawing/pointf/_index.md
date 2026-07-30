---
title: PointF
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje dvojici jednopřesných plovoucích desetinných souřadnic X a Y bodu v dvourozměrné rovině. Tento typ by měl být alokován na zásobníku a předáván do funkcí hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 222
url: /cs/system.drawing/pointf/
---
## PointF třída


Represents a pair of single-precision floating point X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Nikdy nepoužívejte [System::SmartPtr](../../system/smartptr/) třídu to manage objects of this type.

```cpp
class PointF
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Přidá hodnoty šířky a výšky specifikovaného objektu [SizeF](../sizef/) k hodnotám souřadnic X a Y specifikovaného objektu [PointF](./) odpovídajícím způsobem. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Přidá hodnoty šířky a výšky specifikovaného objektu [Size](../size/) k hodnotám souřadnic X a Y specifikovaného objektu [PointF](./) odpovídajícím způsobem. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Určuje, zda je aktuální objekt a specifikovaný objekt rovný, tj. představují stejný pár hodnot souřadnic X a Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Určuje, zda jsou obě hodnoty souřadnic X a Y rovny 0. |
| **float** [get_X](./get_x/)() const | Vrací hodnotu souřadnice X reprezentovanou aktuálním objektem. |
| **float** [get_Y](./get_y/)() const | Vrací hodnotu souřadnice Y reprezentovanou aktuálním objektem. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
| **bool** [IsNull](./isnull/)() const | Vždy vrací false. |
| explicit  [operator bool](./operator_bool/)() | Vždy vrací true. |
|  [PointF](./pointf/)() | Vytvoří nový objekt [PointF](./) a inicializuje jeho hodnoty souřadnic X a Y na 0. |
|  [PointF](./pointf/)(**float**, **float**) | Vytvoří nový objekt [PointF](./) a inicializuje jej specifikovanými hodnotami. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Vytvoří nový objekt [PointF](./) a inicializuje jeho souřadnice X a Y hodnotami šířky a výšky odpovídajícího objektu [SizeF](../sizef/). |
| void [set_X](./set_x/)(**float**) | Nastaví hodnotu souřadnice X reprezentovanou aktuálním objektem. |
| void [set_Y](./set_y/)(**float**) | Nastaví hodnotu souřadnice Y reprezentovanou aktuálním objektem. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Odečte hodnoty šířky a výšky specifikovaného objektu [SizeF](../sizef/) od hodnot souřadnic X a Y specifikovaného objektu [PointF](./) odpovídajícím způsobem. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Odečte hodnoty šířky a výšky specifikovaného objektu [Size](../size/) od hodnot souřadnic X a Y specifikovaného objektu [PointF](./) odpovídajícím způsobem. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Vrací řetězcové znázornění páru hodnot souřadnic X a Y reprezentovaných aktuálním objektem. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | Prázdná instance třídy [PointF](./), jejíž hodnoty souřadnic X a Y jsou 0. |

## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)