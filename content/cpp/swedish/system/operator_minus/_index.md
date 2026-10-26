---
title: operator-()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar antalet dagar mellan två veckodagar.
type: docs
weight: 2172
url: /sv/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) funktion

Beräknar antalet dagar mellan två veckodagar.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | Minuenden |
| b | [DayOfWeek](../dayofweek/) | Subtrahenden |

### Returvärde

Antalet dagar mellan veckodagarna **a** och **b**; returvärdet är ett negativt tal om *går* efter ****

## System::operator-(const T\&, const Decimal\&) funktion

Returnerar en ny instans av [Decimal](../decimal/) klass som representerar ett värde som är resultatet av subtraktion av värdet som representeras av det angivna [Decimal](../decimal/)-objektet från det angivna värdet.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const T\& | Värdet att subtrahera från |
| d | const [Decimal](../decimal/)\& | [Decimal](../decimal/)-objektet som representerar det subtraherade värdet |

### Returvärde

En ny instans av [Decimal](../decimal/) klass som representerar ett värde som är resultatet av subtraktion av värdet som representeras av **d** från **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funktion

Kopplar bort alla återuppringningar i högra delegaten från slutet av vänstra delegatens återuppringningslista.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Delegaten som återuppringningarna ska tas bort från. |
| rhv | MulticastDelegate\<T\> | Delegaten vars återuppringningar kommer att tas bort. |

### Returvärde

Returnerar en delegat som innehåller återuppringningarna från det vänstra värdet, men utan de från det högra värdet.

## System::operator-(const T1\&, const Nullable\<T2\>\&) funktion

Subtraherar icke-nullbara och nullbara värden.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ för vänster operand. |
| T2 | Typ för höger operand. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| some | const T1\& | Vänster operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Höger operand. |

### Returvärde

Subtraktionsresultat.

## Se även

* Enum [DayOfWeek](../dayofweek/)
* Klass [Decimal](../decimal/)
* Klass [Nullable](../nullable/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)