---
title: Round()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zaokrągla podaną wartość do najbliższej liczby całkowitej.
type: docs
weight: 157
url: /pl/system/mathf/round/
---
## MathF::Round(float) metoda

Zaokrągla podaną wartość do najbliższej liczby całkowitej.

```cpp
static float System::MathF::Round(float a)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | **float** | Wartość do zaokrąglenia |

### Wartość zwracana

**a** zaokrąglone do najbliższej liczby całkowitej

## MathF::Round(float, int) metoda

Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr ułamkowych.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr ułamkowych w wynikowej wartości |

### Wartość zwracana

Liczba z określoną liczbą cyfr najbliższa **value**

## MathF::Round(float, MidpointRounding) metoda

Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do zaokrąglenia |
| mode | [MidpointRounding](../../midpointrounding/) | Określa sposób zaokrąglania, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

**value** zaokrąglone do najbliższej liczby całkowitej

## MathF::Round(float, int, MidpointRounding) metoda

Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr ułamkowych. Parametr określa zachowanie funkcji, jeśli podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr ułamkowych w wynikowej wartości |
| mode | [MidpointRounding](../../midpointrounding/) | Określa sposób zaokrąglania, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

Liczba z określoną liczbą cyfr najbliższa **value**

## Zobacz także

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)