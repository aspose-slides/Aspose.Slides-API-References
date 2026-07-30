---
title: Exists()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se l'oggetto Array specificato contiene un elemento che soddisfa i requisiti del predicato specificato.
type: docs
weight: 781
url: /it/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) metodo

Determina se l'oggetto [Array](../) specificato contiene un elemento che soddisfa i requisiti del predicato specificato.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | L'array in cui cercare l'elemento |
| match | std::function\<**bool**(T)> | Oggetto funzione che definisce i requisiti e verifica se un elemento li soddisfa |

### Valore di ritorno

True se **arr** contiene un elemento che soddisfa i requisiti definiti da **match**

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)