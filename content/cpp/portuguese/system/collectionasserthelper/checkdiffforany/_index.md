---
title: CheckDiffForAny()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se algum elemento da coleção atende ao predicado.
type: docs
weight: 27
url: /pt/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) método


Verifica se algum elemento da coleção atende ao predicado.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicado a ser verificado. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valores a serem verificados. |

### Valor de Retorno

True if check suceeds for any element, false if all pass.

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)