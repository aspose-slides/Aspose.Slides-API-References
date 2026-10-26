---
title: DoTryFinally()
second_title: Riferimento API Aspose.Slides per C++
description: La funzione singola che emula il comportamento della dichiarazione try[-catch]-finally di C#. Durante la traduzione della dichiarazione try[-catch]-finally di C# con l'opzione del traduttore finally_statement_as_lambda impostata su true, l'istruzione viene tradotta in una chiamata a questo metodo.
type: docs
weight: 2445
url: /it/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) funzione


La funzione singola che emula il comportamento della dichiarazione try[-catch]-finally di C#. Durante la traduzione della dichiarazione try[-catch]-finally di C# con l'opzione del traduttore finally_statement_as_lambda impostata su true, l'istruzione viene tradotta in una chiamata a questo metodo.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto funzione che implementa la parte try[-catch] della dichiarazione try[-catch]-finally emulata |
| F | Il tipo dell'oggetto funzione che implementa la parte finally della dichiarazione try[-catch]-finally emulata |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tryBlock | T\&& | L'oggetto funzione il cui corpo contiene l'implementazione della parte try[-catch] della dichiarazione try[-catch]-finally emulata |
| finallyBlock | F\&& | L'oggetto funzione il cui corpo contiene l'implementazione della parte finally della dichiarazione try[-catch]-finally emulata |

## System::DoTryFinally(T\&&, F\&&) funzione


La funzione singola che emula il comportamento della dichiarazione try[-catch]-finally di C#. Durante la traduzione della dichiarazione try[-catch]-finally di C# con l'opzione del traduttore finally_statement_as_lambda impostata su true, l'istruzione viene tradotta in una chiamata a questo metodo. Questa overload gestisce il caso in cui il valore di ritorno dell'oggetto funzione che implementa la parte try[-catch] della dichiarazione try[-catch]-finally è bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto funzione che implementa la parte try[-catch] della dichiarazione try[-catch]-finally emulata |
| F | Il tipo dell'oggetto funzione che implementa la parte finally della dichiarazione try[-catch]-finally emulata |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tryBlock | T\&& | L'oggetto funzione il cui corpo contiene l'implementazione della parte try[-catch] della dichiarazione try[-catch]-finally emulata |
| finallyBlock | F\&& | L'oggetto funzione il cui corpo contiene l'implementazione della parte finally della dichiarazione try[-catch]-finally emulata |

## System::DoTryFinally(T\&&, F\&&) funzione


La funzione singola che emula il comportamento della dichiarazione try[-catch]-finally di C#. Durante la traduzione della dichiarazione try[-catch]-finally di C# con l'opzione del traduttore finally_statement_as_lambda impostata su true, l'istruzione viene tradotta in una chiamata a questo metodo. Questa overload gestisce il caso in cui il valore di ritorno dell'oggetto funzione che implementa la parte try[-catch] della dichiarazione try[-catch]-finally è bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto funzione che implementa la parte try[-catch] della dichiarazione try[-catch]-finally emulata |
| F | Il tipo dell'oggetto funzione che implementa la parte finally della dichiarazione try[-catch]-finally emulata |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tryBlock | T\&& | L'oggetto funzione il cui corpo contiene l'implementazione della parte try[-catch] della dichiarazione try[-catch]-finally emulata |
| finallyBlock | F\&& | L'oggetto funzione il cui corpo contiene l'implementazione della parte finally della dichiarazione try[-catch]-finally emulata |

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)