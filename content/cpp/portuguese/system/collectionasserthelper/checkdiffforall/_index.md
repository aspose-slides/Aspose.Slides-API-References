---
title: CheckDiffForAll()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se todos os elementos da coleção aderem ao predicado.
type: docs
weight: 14
url: /pt/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) método


Verifica se todos os elementos da coleção aderem ao predicado.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicado a ser verificado. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valores a serem verificados. |

### Valor de Retorno

Falso se a verificação falhar para algum elemento, verdadeiro se todos passarem.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)