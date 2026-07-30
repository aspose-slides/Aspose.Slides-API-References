---
title: PrintToString()
second_title: Riferimento API di Aspose.Slides per C++
description: Stampa l'oggetto in una stringa selezionando la funzione di serializzazione appropriata.
type: docs
weight: 1
url: /it/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) funzione

Stampa l'oggetto in una stringa selezionando la funzione di serializzazione appropriata.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) da stampare. |

### Valore restituito

[String](../../system/string/) rappresentazioni dell'oggetto passato.

## System::TestPredicates::Details::PrintToString(const T\&) funzione

Stampa i contenitori di tipo ICollection in una stringa stampando i loro elementi (non più di 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) da stampare. |

### Valore restituito

Rappresentazioni concatenate in stringa degli elementi contenuti.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) funzione

Stampa nullptr in una stringa.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Valore restituito

"nullptr" stringa.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) funzione

Stampa le collezioni [IEnumerable<bool>](../../system.collections.generic/ienumerable/) in una stringa stampando i loro elementi (non più di 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Object](../../system/object/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) da stampare. |

### Valore restituito

Rappresentazioni concatenate in stringa degli elementi contenuti.

## Vedi anche

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Struttura [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namespace [System::TestPredicates::Details](../)
* Libreria [Aspose.Slides](../../)