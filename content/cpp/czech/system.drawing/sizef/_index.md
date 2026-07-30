---
title: SizeF
second_title: Aspose.Slides pro C++ API Reference
description: "Representuje dvojici hodnot s jednoduchou přesností s plovoucí desetinnou čárkou, které představují šířku a výšku obrázku. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 287
url: /cs/system.drawing/sizef/
---
## SizeF třída

Representuje dvojici hodnot s jednoduchou přesností s plovoucí desetinnou čárkou, které představují šířku a výšku obrázku. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../../system/smartptr/) k řízení objektů tohoto typu.

```cpp
class SizeF
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Vrátí nový objekt [SizeF](./), který je součtem zadaných objektů [SizeF](./), tj. jehož hodnota šířky je rovna součtu hodnot šířky zadaných objektů a hodnota výšky je rovna součtu hodnot výšky zadaných objektů. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Určuje, zda je aktuální objekt a zadaný objekt roven, tj. představují stejnou dvojici hodnot šířky a výšky. |
| **float** [get_Height](./get_height/)() const | Vrací hodnotu výšky reprezentovanou aktuálním objektem. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Určuje, zda jsou hodnoty šířky i výšky rovny 0. |
| **float** [get_Width](./get_width/)() const | Vrací hodnotu šířky reprezentovanou aktuálním objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
|  [operator PointF](./operator_pointf/)() const | Převede aktuální objekt na instanci objektu [Point](../point/) inicializací jeho X a Y souřadnice odpovídajícími hodnotami šířky a výšky aktuálního objektu. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Přidá hodnoty šířky a výšky zadaného objektu [SizeF](./) k hodnotám šířky a výšky aktuálního objektu [SizeF](./) odpovídajícím způsobem. |
| void [set_Height](./set_height/)(**float**) | Nastaví hodnotu výšky reprezentovanou aktuálním objektem. |
| void [set_Width](./set_width/)(**float**) | Nastaví hodnotu šířky reprezentovanou aktuálním objektem. |
|  [SizeF](./sizef/)() | Vytvoří nový objekt [SizeF](./) a inicializuje jeho hodnoty šířky a výšky na 0. |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Vytvoří nový objekt [SizeF](./) a inicializuje jeho hodnoty šířky a výšky hodnotami X a Y souřadnic zadaného bodu odpovídajícím způsobem. |
|  [SizeF](./sizef/)(**float**, **float**) | Vytvoří nový objekt [SizeF](./) a inicializuje jej zadanými hodnotami. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Vrátí nový objekt [SizeF](./), který je výsledkem odečtení **size2** od **size1**, tj. jeho hodnota šířky je výsledkem odečtení šířky **size2** od šířky **size1** a hodnota výšky je výsledkem odečtení výšky **size2** od výšky **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Převede aktuální objekt na instanci objektu [Point](../point/) inicializací jeho X a Y souřadnice odpovídajícími hodnotami šířky a výšky aktuálního objektu. |
| [Size](../size/) [ToSize](./tosize/)() const | Vytvoří objekt [Size](../size/) z aktuálního objektu [SizeF](./) tak, že ořízne hodnoty šířky a výšky objektu [SizeF](./) na nejbližší nižší celá čísla. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci dvojice hodnot šířky a výšky reprezentovaných aktuálním objektem. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | Prázdná instance třídy [SizeF](./), jejíž hodnoty šířky a výšky jsou 0. |

## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)