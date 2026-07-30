---
title: CharacterRange
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje rozsah pozic znaků v řetězci. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 40
url: /cs/system.drawing/characterrange/
---
## CharacterRange třída


Představuje rozsah pozic znaků v řetězci. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo odkazem. Nikdy nepoužívejte třídu [System::SmartPtr](../../system/smartptr/) k řízení objektů tohoto typu.

```cpp
class CharacterRange
```

## Metody

| Method | Popis |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Vytvoří novou instanci třídy [CharacterRange](./), která představuje zadaný rozsah. |
|  [CharacterRange](./characterrange/)() | Vytvoří novou instanci třídy [CharacterRange](./), která představuje prázdný rozsah. |
| **int32_t** [get_First](./get_first/)() const | Vrací pozici prvního znaku v rozsahu reprezentovaném aktuálním objektem. |
| **int32_t** [get_Length](./get_length/)() const | Vrací počet znaků v rozsahu reprezentovaném aktuálním objektem. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Určuje, zda aktuální a zadané objekty představují odlišné rozsahy. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Určuje, zda aktuální a zadané objekty představují stejný rozsah. |
| void [set_First](./set_first/)(**int32_t**) | Nastaví pozici prvního znaku v rozsahu reprezentovaném aktuálním objektem. |
| void [set_Length](./set_length/)(**int32_t**) | Vrací počet znaků v rozsahu reprezentovaném aktuálním objektem. |
## Viz také

* jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)