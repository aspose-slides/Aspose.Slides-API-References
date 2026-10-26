---
title: operator=()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 92
url: /pt/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) método

```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) método

Desconstrói o objeto para esta tupla de valores.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Um objeto para desconstruir |

## Ver também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ValueTuple](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)