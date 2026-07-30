---
title: operator<()
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 2094
url: /it/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) funzione




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) funzione




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) funzione


Restituisce sempre false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) funzione


Determina se il valore specificato è inferiore al valore rappresentato dall'oggetto [Nullable](../nullable/) specificato applicando [operator<()](./) a questi valori.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del primo valore comparato |
| T2 | Il tipo sottostante dell'oggetto [Nullable](../nullable/) che rappresenta il secondo valore comparato |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| some | const T1\& | Un riferimento costante al valore da usare come primo comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Un riferimento costante all'oggetto [Nullable](../nullable/) il cui valore rappresentato deve essere usato come secondo comparando |

### Valore restituito

True se il primo comparando è inferiore al secondo comparando, altrimenti - false

## System::operator<(std::nullptr_t, TimeSpan) funzione




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Vedi anche

* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)