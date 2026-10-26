---
title: Round()
second_title: Aspose.Slides pro C++ API Reference
description: Zaokrouhlí zadanou hodnotu na nejbližší celé číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům.
type: docs
weight: 404
url: /cs/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) metoda

Zaokrouhlí zadanou hodnotu na nejbližší celé číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | Hodnota k zaokrouhlení |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlování, pokud je **hodnota** stejně blízko ke dvěma nejbližším číslům. |

### Návratová hodnota

**d** zaokrouhlené na nejbližší celé číslo

## Decimal::Round(const Decimal\&, int, MidpointRounding) metoda

Zaokrouhlí zadanou hodnotu na nejbližší hodnotu s určeným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | Hodnota k zaokrouhlení |
| digits | int | Počet desetinných míst ve zaokrouhlené hodnotě |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlování, pokud je **hodnota** stejně blízko ke dvěma nejbližším číslům. |

### Návratová hodnota

Číslo se zadaným počtem desetinných míst nejbližší **hodnotě**

## Viz také

* Výčet [MidpointRounding](../../midpointrounding/)
* Třída [Decimal](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)