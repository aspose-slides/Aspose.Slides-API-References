---
title: Round()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zaokrągla podaną wartość do najbliższej liczby całkowitej.
type: docs
weight: 157
url: /pl/system/math/round/
---
## Math::Round(double) metoda


Zaokrągla podaną wartość do najbliższej liczby całkowitej.

```cpp
static double System::Math::Round(double a)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | **double** | Wartość do zaokrąglenia |

### Wartość zwracana

**a** zaokrąglona do najbliższej liczby całkowitej

## Math::Round(double, int) metoda


Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr dziesiętnych.

```cpp
static double System::Math::Round(double value, int digits)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr dziesiętnych w zaokrąglonej wartości |

### Wartość zwracana

Liczba o określonej liczbie cyfr najbliższa **value**

## Math::Round(double, MidpointRounding) metoda


Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, gdy podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość do zaokrąglenia |
| mode | [MidpointRounding](../../midpointrounding/) | Określa sposób zaokrąglania, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

**value** zaokrąglona do najbliższej liczby całkowitej

## Math::Round(double, int, MidpointRounding) metoda


Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr dziesiętnych. Parametr określa zachowanie funkcji, gdy podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr dziesiętnych w zaokrąglonej wartości |
| mode | [MidpointRounding](../../midpointrounding/) | Określa sposób zaokrąglania, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

Liczba o określonej liczbie cyfr najbliższa **value**

## Math::Round(const Decimal\&) metoda


Zaokrągla podaną wartość do najbliższej liczby całkowitej.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Wartość do zaokrąglenia |

### Wartość zwracana

**d** zaokrąglona do najbliższej liczby całkowitej

## Math::Round(const Decimal\&, int) metoda


Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr dziesiętnych.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr dziesiętnych w zaokrąglonej wartości |

### Wartość zwracana

Liczba o określonej liczbie cyfr najbliższa **value**

## Math::Round(const Decimal\&, MidpointRounding) metoda


Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, gdy podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Wartość do zaokrąglenia |
| mode | [MidpointRounding](../../midpointrounding/) | Określa sposób zaokrąglania, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

**d** zaokrąglona do najbliższej liczby całkowitej

## Math::Round(const Decimal\&, int, MidpointRounding) metoda


Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr dziesiętnych. Parametr określa zachowanie funkcji, gdy podana wartość jest tak samo bliska dwóm najbliższym liczbom.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Wartość do zaokrąglenia |
| digits | int | Liczba cyfr dziesiętnych w zaokrąglonej wartości |
| mode | [MidpointRounding](../../midpointrounding/) | Określa sposób zaokrąglania, jeśli **value** jest tak samo bliska dwóm najbliższym liczbom. |

### Wartość zwracana

Liczba o określonej liczbie cyfr najbliższa **value**

## Zobacz także

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)