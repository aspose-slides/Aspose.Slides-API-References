---
title: Resize()
second_title: Riferimento API di Aspose.Slides per C++
description: Modifica la dimensione dell'array specificato al valore indicato o crea un nuovo array con la dimensione specificata.
type: docs
weight: 768
url: /it/system/array/resize/
---
## Array::Resize(ArrayPtr\<Type\>\&, int) metodo

Modifica la dimensione dell'array specificato al valore indicato oppure crea un nuovo array con la dimensione specificata.

```cpp
template<typename Type> static void System::Array<T>::Resize(ArrayPtr<Type> &arr, int new_size)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | [Array](../) per ridimensionare. Se **arr** è un puntatore nullo, verrà creato un nuovo array |
| new_size | int | La nuova dimensione dell'array, o la dimensione del nuovo array se **arr** è nullo |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Metodo [Type](../../object/type/)
* Classe [Array](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)