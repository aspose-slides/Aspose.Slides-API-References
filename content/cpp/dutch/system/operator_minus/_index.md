---
title: operator-()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent het aantal dagen tussen twee dagen van de week.
type: docs
weight: 2172
url: /nl/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) functie


Berekent het aantal dagen tussen twee dagen van de week.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | The minuend |
| b | [DayOfWeek](../dayofweek/) | The subtrahend |

### Retourwaarde

Het aantal dagen tussen weekdagen **a** en **b**; de retourwaarde is een negatief getal als *goes* after ****

## System::operator-(const T\&, const Decimal\&) functie


Retourneert een nieuw exemplaar van [Decimal](../decimal/) klasse die een waarde vertegenwoordigt die het resultaat is van aftrekking van de waarde die wordt weergegeven door het opgegeven [Decimal](../decimal/) object van de opgegeven waarde.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const T\& | The value to subtract from |
| d | const [Decimal](../decimal/)\& | The [Decimal](../decimal/) object representing the subtracted value |

### Retourwaarde

Een nieuw exemplaar van [Decimal](../decimal/) klasse die een waarde vertegenwoordigt die het resultaat is van aftrekking van de waarde die door **d** wordt weergegeven van **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) functie


Ontkoppelt alle callbacks in de delegate van de rechterhand van het einde van de callbacklijst van de delegate van de linkerhand.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate from which callbacks will be removed. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks will be removed. |

### Retourwaarde

Retourneert een delegate die de callbacks van de linkerhandwaarde bevat, maar zonder die van de rechterhandwaarde.

## System::operator-(const T1\&, const Nullable\<T2\>\&) functie


Trekt niet-nullbare en nullable waarden van elkaar af.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Left operand type. |
| T2 | Right operand type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| some | const T1\& | Left operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Right operand. |

### Retourwaarde

Resultaat van de aftrekking.

## Zie ook

* Enum [DayOfWeek](../dayofweek/)
* Klasse [Decimal](../decimal/)
* Klasse [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)