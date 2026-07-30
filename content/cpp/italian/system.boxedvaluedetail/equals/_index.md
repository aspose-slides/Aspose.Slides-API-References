---
title: Equals()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina l'uguaglianza del valore specificato utilizzando l'operatore ==().
type: docs
weight: 66
url: /it/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) funzione

Determina l'uguaglianza del valore specificato utilizzando [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| The | tipo dei valori da confrontare |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | Il primo comparando |
| value2 | T | Il secondo comparando |

### Valore di ritorno

True se il valore specificato è uguale come determinato da [operator==()](../../system/operator_equal_equal/), altrimenti - false

## System::BoxedValueDetail::Equals(T, T) funzione

Determina l'uguaglianza del valore specificato utilizzando il metodo [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| The | tipo dei valori da confrontare |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | Il primo comparando |
| value2 | T | Il secondo comparando |

### Valore di ritorno

True se il valore specificato è uguale come determinato dal metodo [Equals()](./), altrimenti - false

## Vedi anche

* Spazio dei nomi [System::BoxedValueDetail](../)
* Libreria [Aspose.Slides](../../)