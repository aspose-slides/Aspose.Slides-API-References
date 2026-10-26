---
title: Equals< float, float >()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Specializace pro hodnoty s jednoduchou přesností. Ačkoli dva floating point NaN jsou definovány normou IEC 60559:1989 tak, že se vždy porovnávají jako různé, smlouva pro System.Object.Equals vyžaduje, aby přepsané metody splňovaly požadavky ekvivalenčního operátoru. Proto System.Double.Equals a System.Single.Equals vrací True při porovnání dvou NaN, zatímco operátor rovnosti vrací False v tomto případě, jak vyžaduje standard."
type: docs
weight: 2705
url: /cs/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) funkce

Specializace pro hodnoty s jednoduchou přesností. Ačkoli dva floating point NaN jsou definovány normou IEC 60559:1989 tak, že se vždy porovnají jako různé, smlouva pro [System.Object.Equals](../object/equals/) vyžaduje, aby přepsané metody splňovaly požadavky ekvivalenčního operátoru. Proto System.Double.Equals a System.Single.Equals vracejí True při porovnání dvou NaN, zatímco operátor rovnosti vrací False v tomto případě, jak požaduje standard.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | const **float**\& | První porovnávaný operand |
| b | const **float**\& | Druhý porovnávaný operand |

### Návratová hodnota

True pokud jsou obě hodnoty NaN nebo jsou stejné, jinak - false

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)