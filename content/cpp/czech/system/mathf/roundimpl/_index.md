---
title: RoundImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.
type: docs
weight: 287
url: /cs/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) metoda


Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **float** | Hodnota k zaokrouhlení |
| digits | int | Počet desetinných míst zaokrouhlené hodnoty |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlení, pokud je **value** stejně blízká ke dvěma nejbližším číslům. |

### Návratová hodnota

Číslo se zadaným počtem číslic nejbližší **value**

## Viz také

* Výčtový typ [MidpointRounding](../../midpointrounding/)
* Struktura [MathF](../)
* jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)