---
title: FindIndex()
second_title: Aspose.Slides para C++ Referência da API
description: Pesquisa o primeiro elemento no array especificado que satisfaz as condições do predicado especificado.
type: docs
weight: 638
url: /pt/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) método


Pesquisa o primeiro elemento no array especificado que satisfaz as condições do predicado especificado.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) para pesquisar um elemento em |
| match | [System::Predicate](../../predicate/)\<T\> | Um predicado que define as condições para corresponder aos elementos da matriz |

### Valor de retorno

O índice do primeiro elemento na matriz que satisfaz as condições definidas pelo predicado, caso contrário -1

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)