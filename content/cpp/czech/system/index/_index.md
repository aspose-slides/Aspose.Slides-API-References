---
title: Index
second_title: Aspose.Slides pro C++ API Reference
description: "Představuje index do kolekce. Index může být od začátku nebo od konce. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte System::SmartPtr třídu k řízení objektů tohoto typu."
type: docs
weight: 1015
url: /cs/system/index/
---
## Index třída


Představuje index do kolekce. Index může být od začátku nebo od konce. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte [System::SmartPtr](../smartptr/) třídu k řízení objektů tohoto typu.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Určuje, zda aktuální instance a specifikovaná [Index](./) představují stejnou pozici. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Vytvoří [Index](./) relativní k konci kolekce. |
| static constexpr [Index](./) [get_End](./get_end/)() | Získá objekt [Index](./) představující konec kolekce. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Získá hodnotu, která určuje, zda je index od konce. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Získá objekt [Index](./) představující začátek kolekce. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Získá hodnotu indexu. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Vrátí hash kód pro aktuální index. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Převede aktuální [Index](./) na offset od začátku kolekce se zadanou délkou. |
| constexpr [Index](./index/)() | Vytvoří instanci představující začátek kolekce. |
| constexpr [Index](./index/)(**int32_t**) | Vytvoří instanci představující zadanou pozici od začátku kolekce. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Vytvoří instanci představující zadaný index. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)