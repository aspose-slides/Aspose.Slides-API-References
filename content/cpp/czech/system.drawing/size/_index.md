---
title: Size
second_title: Aspose.Slides pro C++ API referenci
description: "Reprezentuje dvojici celočíselných hodnot, které představují šířku a výšku obrázku. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 274
url: /cs/system.drawing/size/
---
## Size třída

Reprezentuje dvojici celočíselných hodnot, které představují šířku a výšku obrázku. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte [System::SmartPtr](../../system/smartptr/) třídu k řízení objektů tohoto typu.

```cpp
class Size
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Vrací nový objekt [Size](./), který je součtem zadaného objektu [Size](./), tj. jehož hodnota šířky je rovna součtu hodnot šířky zadaných objektů a hodnota výšky je rovna součtu hodnot výšky zadaných objektů. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Vytvoří objekt [Size](./) ze zadaného objektu [SizeF](../sizef/) zaokrouhlením hodnot šířky a výšky objektu [SizeF](../sizef/) na následující vyšší celočíselné hodnoty. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Určuje, zda jsou aktuální objekt a zadaný objekt stejné, tj. představují stejnou dvojici hodnot šířky a výšky. |
| int [get_Height](./get_height/)() const | Vrací hodnotu výšky reprezentovanou aktuálním objektem. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Určuje, zda jsou hodnoty šířky i výšky rovny 0. |
| int [get_Width](./get_width/)() const | Vrací hodnotu šířky reprezentovanou aktuálním objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
|  [operator Point](./operator_point/)() const | Vytvoří instanci objektu [Point](../point/) a inicializuje jeho souřadnice X a Y odpovídajícím způsobem hodnotami šířky a výšky aktuálního objektu. |
|  [operator SizeF](./operator_sizef/)() const | Vytvoří instanci objektu [SizeF](../sizef/) a inicializuje ji hodnotami šířky a výšky aktuálního objektu [Size](./). |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Vytvoří objekt [Size](./) ze zadaného objektu [SizeF](../sizef/) zaokrouhlením hodnot šířky a výšky objektu [SizeF](../sizef/) na nejbližší celočíselné hodnoty. |
| void [set_Height](./set_height/)(int) | Nastavuje hodnotu výšky reprezentovanou aktuálním objektem. |
| void [set_Width](./set_width/)(int) | Nastavuje hodnotu šířky reprezentovanou aktuálním objektem. |
|  [Size](./size/)() | Vytvoří nový objekt [Size](./) a inicializuje jeho hodnoty šířky a výšky na 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Vytvoří nový objekt [Size](./) a inicializuje jeho hodnoty šířky a výšky hodnotami souřadnic X a Y zadaného bodu. |
|  [Size](./size/)(int, int) | Vytvoří nový objekt [Size](./) a inicializuje jej zadanou hodnotou. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Vrací nový objekt [Size](./), který je výsledkem odčítání **size2** od **size1**, tj. jehož hodnota šířky je výsledkem odečtení hodnoty šířky **size2** od hodnoty šířky **size1** a hodnota výšky je výsledkem odečtení hodnoty výšky **size2** od hodnoty výšky **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci dvojice hodnot šířky a výšky reprezentovaných aktuálním objektem. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Vytvoří objekt [Size](./) ze zadaného objektu [SizeF](../sizef/) zkrácením hodnot šířky a výšky objektu [SizeF](../sizef/) na následující nižší celočíselné hodnoty. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | Prázdná instance třídy [Size](./), jejíž hodnoty šířky a výšky jsou 0. |

## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)