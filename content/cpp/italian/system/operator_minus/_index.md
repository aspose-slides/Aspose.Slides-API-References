---
title: operator-()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola il numero di giorni tra due giorni della settimana.
type: docs
weight: 2172
url: /it/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) funzione

Calcola il numero di giorni tra due giorni della settimana.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | Il minuendo |
| b | [DayOfWeek](../dayofweek/) | Il sottraendo |

### Valore di ritorno

Il numero di giorni tra i giorni della settimana **a** e **b**; il valore restituito è un numero negativo se *segue* dopo ****

## System::operator-(const T\&, const Decimal\&) funzione

Restituisce una nuova istanza della classe [Decimal](../decimal/) che rappresenta un valore che è il risultato della sottrazione del valore rappresentato dall'oggetto [Decimal](../decimal/) specificato dal valore specificato.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const T\& | Il valore da cui sottrarre |
| d | const [Decimal](../decimal/)\& | L'oggetto [Decimal](../decimal/) che rappresenta il valore sottratto |

### Valore di ritorno

Una nuova istanza della classe [Decimal](../decimal/) che rappresenta un valore che è il risultato della sottrazione del valore rappresentato da **d** da **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funzione

Disconnette tutti i callback nella delega della mano destra dalla fine dell'elenco dei callback della delega della mano sinistra.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | La delega dalla quale verranno rimossi i callback. |
| rhv | MulticastDelegate\<T\> | La delega i cui callback verranno rimossi. |

### Valore di ritorno

Restituisce una delega che contiene i callback del valore della mano sinistra, ma senza quelli del valore della mano destra.

## System::operator-(const T1\&, const Nullable\<T2\>\&) funzione

Sottrae valori non nullable e nullable.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo dell'operando sinistro. |
| T2 | Tipo dell'operando destro. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| some | const T1\& | Operando sinistro. |
| other | const [Nullable](../nullable/)\<T2\>\& | Operando destro. |

### Valore di ritorno

Risultato della sottrazione.

## Vedi anche

* Enumerazione [DayOfWeek](../dayofweek/)
* Classe [Decimal](../decimal/)
* Classe [Nullable](../nullable/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)