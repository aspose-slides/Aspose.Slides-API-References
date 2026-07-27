---
title: TrueForAll()
second_title: Referência da API Aspose.Slides para C++
description: Determina se todos os elementos no array especificado atendem às condições definidas pelo predicado especificado.
type: docs
weight: 677
url: /pt/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) método


Determina se todos os elementos no array especificado atendem às condições definidas pelo predicado especificado.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elementos contra os quais combinar as condições |
| match | [System::Predicate](../../predicate/)\<T\> | Um predicado que define as condições para combinar os elementos do array |

### Valor de retorno

true se todos os elementos do array arr atendem às condições definidas pelo predicado match, caso contrário false

## Ver também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)