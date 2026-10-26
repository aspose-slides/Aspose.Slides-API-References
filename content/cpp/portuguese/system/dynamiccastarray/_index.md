---
title: DynamicCastArray()
second_title: Referência da API Aspose.Slides para C++
description: Realiza a conversão dos elementos do array especificado para um tipo diferente.
type: docs
weight: 2991
url: /pt/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) função


Realiza a conversão dos elementos do array especificado para um tipo diferente.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| To | O tipo para o qual os elementos do array especificado devem ser convertidos |
| From | O tipo dos elementos do array cujos elementos serão convertidos |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Ponteiro compartilhado para o array que contém os elementos a serem convertidos |

### Valor de retorno

Um ponteiro para um novo array contendo elementos do tipo **To** equivalentes aos elementos de **from**

Obsoleto
:   Adicionado para compatibilidade retroativa. Use ExplicitCast em vez disso.

## Ver também

* Typedef [SharedPtr](../sharedptr/)
* Classe [Array](../array/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)