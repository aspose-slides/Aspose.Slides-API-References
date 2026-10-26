---
title: operator+()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce una nuova istanza della classe Decimal che rappresenta un valore che è la somma del valore specificato e del valore rappresentato dall'oggetto Decimal specificato.
type: docs
weight: 2185
url: /it/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) funzione

Restituisce una nuova istanza della classe [Decimal](../decimal/) che rappresenta un valore che è la somma del valore specificato e del valore rappresentato dall'oggetto [Decimal](../decimal/) specificato.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const T\& | Il primo addendo |
| d | const [Decimal](../decimal/)\& | Il riferimento costante all'oggetto [Decimal](../decimal/) che rappresenta il secondo addendo |

### Valore restituito

Una nuova istanza della classe [Decimal](../decimal/) che rappresenta un valore che è la somma di **x** e del valore rappresentato da **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) funzione

Collega tutti i callback del delegato destro alla fine della lista dei callback del delegato sinistro.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Il delegato a cui vengono aggiunti i callback. |
| rhv | MulticastDelegate\<T\> | Il delegato i cui callback vengono aggiunti. |

### Valore restituito

Restituisce un delegato che contiene i callback del valore sinistro e poi quelli del valore destro.

## System::operator+(const T1\&, const Nullable\<T2\>\&) funzione

Somma valori non nullable e nullable.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
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

### Valore restituito

Risultato della somma.

## System::operator+(T\&, const String\&) funzione

[String](../string/) concatenazione.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo letterale [String](../string/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | T\& | Letterale da concatenare alla stringa. |
| right | const [String](../string/)\& | [String](../string/) da concatenare. |

### Valore restituito

Stringa concatenata.

## System::operator+(T\&, const String\&) funzione

[String](../string/) concatenazione.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo puntatore [String](../string/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | T\& | Puntatore [String](../string/) da concatenare alla stringa. |
| right | const [String](../string/)\& | [String](../string/) da concatenare. |

### Valore restituito

Stringa concatenata.

## System::operator+(const char_t, const String\&) funzione

[String](../string/) concatenazione.

```cpp
String System::operator+(const char_t left, const String &right)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | const char_t | Carattere da concatenare alla stringa. |
| right | const [String](../string/)\& | [String](../string/) da concatenare. |

### Valore restituito

Stringa concatenata.

## Vedi anche

* Classe [Decimal](../decimal/)
* Classe [Nullable](../nullable/)
* Classe [String](../string/)
* Struttura [IsStringLiteral](../isstringliteral/)
* Struttura [IsStringPointer](../isstringpointer/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)