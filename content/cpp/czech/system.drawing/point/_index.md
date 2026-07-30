---
title: Point
second_title: Aspose.Slides pro C++ - API reference
description: "Representuje dvojici celočíselných souřadnic X a Y bodu ve dvourozměrné rovině. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 209
url: /cs/system.drawing/point/
---
## Point třída


Representuje dvojici celočíselných souřadnic X a Y bodu v dvourozměrné rovině. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu [System::SmartPtr](../../system/smartptr/) k řízení objektů tohoto typu.

```cpp
class Point
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Přidá hodnoty šířky a výšky zadaného objektu [Size](../size/) k hodnotám souřadnic X a Y zadaného objektu [Point](./) odpovídajícím způsobem. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Vytvoří objekt [Point](./) ze zadaného objektu [PointF](../pointf/) zaokrouhlením hodnot X a Y souřadnic objektu [PointF](../pointf/) na nejbližší vyšší celé hodnoty. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Určuje, zda je aktuální objekt a zadaný objekt rovný, tj. představují stejnou dvojici hodnot X a Y souřadnic. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Určuje, zda jsou hodnoty X a Y souřadnic obě rovny 0. |
| int [get_X](./get_x/)() const | Vrací hodnotu souřadnice X reprezentovanou aktuálním objektem. |
| int [get_Y](./get_y/)() const | Vrací hodnotu souřadnice Y reprezentovanou aktuálním objektem. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
| size_t [getStdHash](./getstdhash/)() const | Vrací hash hodnotu pro aktuální objekt. |
| **bool** [IsNull](./isnull/)() const | Vždy vrací false. |
| void [Offset](./offset/)(int, int) | Posune hodnoty X a Y souřadnic reprezentované aktuálním objektem o zadané hodnoty. |
| void [Offset](./offset/)([Point](./)) | Posune souřadnice X a Y reprezentované aktuálním objektem o hodnoty X a Y souřadnic reprezentovaných zadaným objektem [Point](./) odpovídajícím způsobem. |
|  [operator PointF](./operator_pointf/)() const | Vytvoří instanci objektu [PointF](../pointf/) a inicializuje ji hodnotami X a Y souřadnic aktuálního objektu [Point](./). |
|  [operator Size](./operator_size/)() const | Vytvoří instanci objektu [Size](../size/) a inicializuje její hodnoty šířky a výšky hodnotami X a Y souřadnic reprezentovanými aktuálním objektem odpovídajícím způsobem. |
|  [Point](./point/)() | Vytvoří nový objekt [Point](./) a inicializuje jeho hodnoty X a Y souřadnic na 0. |
|  [Point](./point/)(int, int) | Vytvoří nový objekt [Point](./) a inicializuje jej zadanými hodnotami. |
|  [Point](./point/)(const [Size](../size/)\&) | Vytvoří nový objekt [Point](./) a inicializuje jeho hodnoty X a Y souřadnic hodnotami šířky a výšky zadaného objektu [SizeF](../sizef/) odpovídajícím způsobem. |
|  [Point](./point/)(int) | Vytvoří nový objekt [Point](./) a inicializuje jeho hodnotu X souřadnice hodnotou vytvořenou z vyšších 16 bitů zadaného 32-bitového celého čísla a jeho hodnotu Y souřadnice hodnotou vytvořenou z nižších 16 bitů zadaného 32-bitového celého čísla. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Vytvoří objekt [Point](./) ze zadaného objektu [PointF](../pointf/) zaokrouhlením hodnot X a Y souřadnic objektu [PointF](../pointf/) na nejbližší celé hodnoty. |
| void [set_X](./set_x/)(int) | Nastaví hodnotu X souřadnice reprezentovanou aktuálním objektem. |
| void [set_Y](./set_y/)(int) | Nastaví hodnotu Y souřadnice reprezentovanou aktuálním objektem. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Odečte hodnoty šířky a výšky zadaného objektu [Size](../size/) od hodnot X a Y souřadnic zadaného objektu [Point](./) odpovídajícím způsobem. |
| [String](../../system/string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci dvojice hodnot X a Y souřadnic reprezentovaných aktuálním objektem. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Vytvoří objekt [Point](./) ze zadaného objektu [PointF](../pointf/) oříznutím hodnot X a Y souřadnic objektu [PointF](../pointf/) na následující nižší celou hodnotu. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | Prázdná instance třídy [Point](./), jejíž hodnoty X a Y souřadnic jsou 0. |

## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)