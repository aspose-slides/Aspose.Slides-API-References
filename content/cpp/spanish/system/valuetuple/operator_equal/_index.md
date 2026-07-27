---
title: operator=()
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 92
url: /es/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) método




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) método


Descompone el objeto a esta tupla de valores.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Un objeto para descomponer |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [ValueTuple](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)