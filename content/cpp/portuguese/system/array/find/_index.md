---
title: Find()
second_title: Referência da API Aspose.Slides para C++
description: Procura o primeiro elemento no array especificado que satisfaça as condições do predicado especificado.
type: docs
weight: 651
url: /pt/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) método


Procura o primeiro elemento no array especificado que satisfaça as condições do predicado especificado.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) para pesquisar um elemento em |
| match | [System::Predicate](../../predicate/)\<T\> | Um predicado que define as condições para comparar os elementos do array |

### Valor de Retorno

Cópia do primeiro elemento no array que satisfaz as condições definidas pelo predicado, caso contrário valor padrão do tipo T

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)