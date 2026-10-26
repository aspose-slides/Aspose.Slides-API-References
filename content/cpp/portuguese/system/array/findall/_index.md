---
title: FindAll()
second_title: Referência da API Aspose.Slides para C++
description: Recupera todos os elementos que correspondem às condições definidas pelo predicado especificado.
type: docs
weight: 664
url: /pt/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) método

Recupera todos os elementos que correspondem às condições definidas pelo predicado especificado.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) para pesquisar elementos em |
| match | [System::Predicate](../../predicate/)\<T\> | Um predicado que define as condições para corresponder aos elementos do array |

### Valor de Retorno

Um [Array](../) contendo todos os elementos que correspondem às condições definidas pelo predicado especificado, se encontrado; caso contrário, um [Array](../) vazio.

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)