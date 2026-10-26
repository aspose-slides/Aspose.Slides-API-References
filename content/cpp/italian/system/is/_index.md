---
title: Is()
second_title: Riferimento API Aspose.Slides per C++
description: Implementa la traduzione del pattern di dichiarazione 'is'.
type: docs
weight: 2302
url: /it/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) funzione


Implementa la traduzione del pattern di dichiarazione 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| PatternT | tipo da controllare. |
| ExpressionT | tipo dell'espressione sinistra. |
| ResultT | tipo dell'espressione risultato. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | const ExpressionT\& | espressione che verrà controllata. |
| result | ResultT\& | variabile a cui verrà assegnato il tipo controllato. |

### Valore di ritorno

true se il controllo del tipo ha successo, false altrimenti.

## System::Is(const ExpressionT\&, const ConstantT\&) funzione


Implementa la traduzione del pattern costante 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ExpressionT | tipo dell'espressione sinistra. |
| ConstantT | tipo dell'espressione costante. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | const ExpressionT\& | espressione che verrà controllata. |
| constant | const ConstantT\& | espressione che verrà confrontata con quella sinistra. |

### Valore di ritorno

true se il controllo del tipo ha successo, false altrimenti.

## System::Is(const E\&, const A\&) funzione


Funzione di confronto di livello superiore. Applica un pattern a un valore.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| A | tipo del pattern (deve ereditare da Details::Pattern). |
| E | tipo del valore da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| e | const E\& | Valore da confrontare. |
| a | const A\& | Pattern da applicare. |

### Valore di ritorno

true se il pattern corrisponde al valore.

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)