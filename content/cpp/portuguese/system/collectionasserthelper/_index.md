---
title: CollectionAssertHelper
second_title: Referência da API Aspose.Slides para C++
description: API Heler para operações relacionadas a coleções.
type: docs
weight: 1548
url: /pt/system/collectionasserthelper/
---
## CollectionAssertHelper struct

Heler API para operações relacionadas a coleções.

```cpp
class CollectionAssertHelper
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Verifica se todos os elementos da coleção aderem ao predicado. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Verifica se algum elemento da coleção adere ao predicado. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serializa duas coleções para representação de mensagem. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Converte a coleção em string juntando as representações em string dos elementos. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Calcula a 'diff' entre duas coleções. Para cada elemento de cada coleção como chave, o valor resultante será positivo se o elemento ocorrer mais vezes na coleção \"expected\", negativo se o elemento ocorrer mais vezes na coleção \"actual\" e zero se o elemento ocorrer o mesmo número de vezes em cada coleção. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formata a string a ser usada como texto da mensagem. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)