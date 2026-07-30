---
title: Range
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje rozsah s počátečním a koncovým indexem. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k správě objektů tohoto typu."
type: docs
weight: 1197
url: /cs/system/range/
---
## Range třída

Reprezentuje rozsah s počátečním a koncovým indexem. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k správě objektů tohoto typu.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Popis |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Vytvoří rozsah, který začíná na začátku kolekce a končí na zadaném koncovém indexu. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Určuje, zda je aktuální rozsah roven zadanému rozsahu. |
| static constexpr [Range](./) [get_All](./get_all/)() | Vrací [Range](./), který představuje celou kolekci. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Získá index End. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Získá index Start. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální rozsah. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Vypočítá nulovým založený počáteční posun a délku pro zadanou délku kolekce. |
| constexpr [Range](./range/)() | Vytvoří prázdný rozsah. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Vytvoří [Range](./) ze zadaných počátečních a koncových indexů. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Vytvoří rozsah, který začíná na zadaném počátečním indexu a rozšiřuje se až do konce kolekce. |
## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)