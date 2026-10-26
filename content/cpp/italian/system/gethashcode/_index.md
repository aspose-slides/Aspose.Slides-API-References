---
title: GetHashCode()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un codice hash per il valore scalare specificato.
type: docs
weight: 2484
url: /it/system/gethashcode/
---
## System::GetHashCode(const T\&) funzione

Restituisce un codice hash per il valore scalare specificato.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo del valore per il quale la funzione genera il codice hash |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Il valore per il quale generare il codice hash |

### Valore restituito

Il codice hash generato per il valore specificato

## System::GetHashCode(const T\&) funzione

Restituisce un codice hash per l'oggetto specificato.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto per il quale la funzione genera il codice hash |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Il [SmartPtr](../smartptr/) che punta all'oggetto per il quale generare il codice hash |

### Valore restituito

Il codice hash generato per l'oggetto specificato

## System::GetHashCode(const T\&) funzione

Restituisce un codice hash per l'oggetto specificato che è un'eccezione.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto per il quale la funzione genera il codice hash |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Il Exception Wrapper che contiene l'oggetto per il quale generare il codice hash |

### Valore restituito

Il codice hash generato per l'oggetto specificato

## System::GetHashCode(const T\&) funzione

Restituisce un codice hash per l'oggetto specificato che non è un puntatore intelligente né un'eccezione.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto per il quale la funzione genera il codice hash |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Una const reference all'oggetto per il quale generare il codice hash |

### Valore restituito

Il codice hash generato per l'oggetto specificato

## System::GetHashCode(const std::thread::id\&) funzione

Specializzazione per std::thread::id; restituisce il codice hash per l'oggetto thread specificato.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Vedi anche

* Struttura [IsSmartPtr](../issmartptr/)
* Struttura [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)