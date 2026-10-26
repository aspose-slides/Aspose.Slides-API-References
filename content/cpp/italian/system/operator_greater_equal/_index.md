---
title: operator>=()
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 2133
url: /it/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) funzione




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) funzione




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) funzione


Restituisce sempre falso.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) funzione


Determina se il valore specificato è maggiore o uguale al valore rappresentato dall'oggetto [Nullable](../nullable/) specificato applicando [operator>=()](./) a questi valori.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del primo valore comparando |
| T2 | Il tipo sottostante dell'oggetto [Nullable](../nullable/) che rappresenta il secondo valore comparando |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| some | const T1\& | Un riferimento costante al valore da usare come primo comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Un riferimento costante all'oggetto [Nullable](../nullable/) il cui valore rappresentato deve essere usato come secondo comparando |

### Valore di ritorno

Vero se il primo comparando è maggiore o uguale al secondo comparando, altrimenti - falso

## System::operator>=(std::nullptr_t, TimeSpan) funzione




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## Vedi anche

* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Nullable](../nullable/)
* Classe [TimeSpan](../timespan/)
* Struttura [IsNullable](../isnullable/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)