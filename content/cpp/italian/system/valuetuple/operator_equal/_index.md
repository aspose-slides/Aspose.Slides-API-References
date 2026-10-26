---
title: operator=()
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 92
url: /it/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) metodo




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) metodo


Decompone l'oggetto in questa tupla di valori.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Un oggetto da decompilare |

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ValueTuple](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)