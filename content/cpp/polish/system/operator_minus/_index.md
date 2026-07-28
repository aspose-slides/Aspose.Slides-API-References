---
title: operator-()
second_title: Aspose.Slides dla C++ API Referencja
description: Oblicza liczbę dni pomiędzy dwoma dniami tygodnia.
type: docs
weight: 2172
url: /pl/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) funkcja


Oblicza liczbę dni pomiędzy dwoma dniami tygodnia.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | The minuend |
| b | [DayOfWeek](../dayofweek/) | The subtrahend |

### Wartość zwracana

Liczba dni pomiędzy dniami tygodnia **a** i **b**; wartość zwracana jest liczbą ujemną, jeśli *przechodzi* po ****

## System::operator-(const T\&, const Decimal\&) funkcja


Zwraca nową instancję klasy [Decimal](../decimal/) , która reprezentuje wartość będącą wynikiem odjęcia wartości reprezentowanej przez określony obiekt [Decimal](../decimal/) od podanej wartości.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T\& | Wartość, od której odejmować |
| d | const [Decimal](../decimal/)\& | obiekt [Decimal](../decimal/) reprezentujący odejmowaną wartość |

### Wartość zwracana

Nowa instancja klasy [Decimal](../decimal/) , która reprezentuje wartość będącą wynikiem odjęcia wartości reprezentowanej przez **d** od **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funkcja


Usuwa wszystkie wywołania zwrotne w delegacie prawej ręki z końca listy wywołań zwrotnych delegata lewej ręki.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate from which callbacks will be removed. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks will be removed. |

### Wartość zwracana

Zwraca delegata, który zawiera wywołania zwrotne lewej wartości, ale bez wywołań zwrotnych prawej wartości.

## System::operator-(const T1\&, const Nullable\<T2\>\&) funkcja


Odejmuje wartości niepuste i dopuszczające null.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T1 | Typ lewego operandu. |
| T2 | Typ prawego operandu. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | Lewy operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Prawy operand. |

### Wartość zwracana

Wynik odejmowania.

## Zobacz także

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)