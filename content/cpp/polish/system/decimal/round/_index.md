---
title: Round()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom.
type: docs
weight: 404
url: /pl/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) metoda


Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| d | const [Decimal](../)\& | Wartość do zaokrąglenia |
| mode | [MidpointRounding](../../midpointrounding/) | Określa, jak wykonać zaokrąglanie, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

**d** zaokrąglone do najbliższej wartości całkowitej

## Decimal::Round(const Decimal\&, int, MidpointRounding) metoda


Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr dziesiętnych. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| d | const [Decimal](../)\& | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr dziesiętnych w zaokrąglonej wartości |
| mode | [MidpointRounding](../../midpointrounding/) | Określa, jak wykonać zaokrąglanie, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

Liczba o określonej liczbie cyfr najbliższa **value**

## Zobacz także

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)