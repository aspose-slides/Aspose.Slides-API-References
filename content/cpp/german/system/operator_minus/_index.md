---
title: operator-()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet die Anzahl der Tage zwischen zwei Wochentagen.
type: docs
weight: 2172
url: /de/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) Funktion


Berechnet die Anzahl der Tage zwischen zwei Wochentagen.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | Der Minuend |
| b | [DayOfWeek](../dayofweek/) | Der Subtrahend |

### Rückgabewert

Die Anzahl der Tage zwischen den Wochentagen **a** und **b**; der Rückgabewert ist eine negative Zahl, wenn *goes* nach ****

## System::operator-(const T\&, const Decimal\&) Funktion


Gibt eine neue Instanz der [Decimal](../decimal/) Klasse zurück, die einen Wert darstellt, der das Ergebnis der Subtraktion des von dem angegebenen [Decimal](../decimal/) Objekt dargestellten Werts vom angegebenen Wert ist.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const T\& | Der Wert, von dem subtrahiert wird |
| d | const [Decimal](../decimal/)\& | Das [Decimal](../decimal/) Objekt, das den subtrahierten Wert darstellt |

### Rückgabewert

Eine neue Instanz der [Decimal](../decimal/) Klasse, die einen Wert darstellt, der das Ergebnis der Subtraktion des von **d** dargestellten Werts von **x** ist.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) Funktion


Entfernt alle Rückrufe im rechten Delegaten vom Ende der Rückrufliste des linken Delegaten.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Der Delegat, aus dem Rückrufe entfernt werden. |
| rhv | MulticastDelegate\<T\> | Der Delegat, dessen Rückrufe entfernt werden. |

### Rückgabewert

Gibt einen Delegaten zurück, der die Rückrufe des linken Werts enthält, jedoch ohne die des rechten Werts.

## System::operator-(const T1\&, const Nullable\<T2\>\&) Funktion


Subtrahiert nicht-nullbare und nullable Werte.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Linker Operandtyp. |
| T2 | Rechter Operandtyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| some | const T1\& | Linker Operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Rechter Operand. |

### Rückgabewert

Subtraktionsergebnis.

## Siehe auch

* Enum [DayOfWeek](../dayofweek/)
* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)