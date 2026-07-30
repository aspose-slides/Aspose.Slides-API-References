---
title: operator-()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vypočítá počet dnů mezi dvěma dny v týdnu.
type: docs
weight: 2172
url: /cs/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) funkce

Vypočítá počet dnů mezi dvěma dny v týdnu.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | menšenec |
| b | [DayOfWeek](../dayofweek/) | menšitel |

### Návratová hodnota

Počet dnů mezi dny v týdnu **a** a **b**; návratová hodnota je záporné číslo, pokud *goes* after ****

## System::operator-(const T\&, const Decimal\&) funkce

Vrátí novou instanci třídy [Decimal](../decimal/), která představuje hodnotu, která je výsledkem odečtení hodnoty zastoupené zadaným objektem [Decimal](../decimal/) od zadané hodnoty.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const T\& | Hodnota, od které se odečítá |
| d | const [Decimal](../decimal/)\& | Objekt [Decimal](../decimal/) představující odečítanou hodnotu |

### Návratová hodnota

Nová instance třídy [Decimal](../decimal/), která představuje hodnotu, která je výsledkem odečtení hodnoty zastoupené **d** od **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funkce

Odpojí všechny zpětné volání v pravém delegátu od konce seznamu zpětných volání levého delegátu.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegát, ze kterého budou zpětná volání odstraněna. |
| rhv | MulticastDelegate\<T\> | Delegát, jehož zpětná volání budou odstraněna. |

### Návratová hodnota

Vrátí delegáta, který obsahuje zpětná volání levé hodnoty, ale bez zpětných volání pravé hodnoty.

## System::operator-(const T1\&, const Nullable\<T2\>\&) funkce

Odečte nenulové a nulovatelné hodnoty.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ levého operandu. |
| T2 | Typ pravého operandu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| some | const T1\& | Levý operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Pravý operand. |

### Návratová hodnota

Výsledek odečtu.

## Viz také

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)