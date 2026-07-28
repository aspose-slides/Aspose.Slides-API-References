---
title: RoundImpl()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. Parametr określa zachowanie funkcji, jeśli podana wartość jest równo odległa od dwóch najbliższych liczb.
type: docs
weight: 287
url: /pl/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) metoda

Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr po przecinku. Parametr określa zachowanie funkcji, jeśli **value** jest równo odległa od dwóch najbliższych liczb.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr po przecinku w zaokrąglonej wartości |
| mode | [MidpointRounding](../../midpointrounding/) | Określa sposób wykonania zaokrąglenia, jeśli **value** jest równo odległa od dwóch najbliższych liczb. |

### Wartość zwracana

Liczba o podanej liczbie cyfr najbliższa **value**

## Zobacz także

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)