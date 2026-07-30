---
title: CollectionAssertHelper
second_title: Riferimento API Aspose.Slides per C++
description: Heler API per operazioni relative alle collezioni.
type: docs
weight: 1548
url: /it/system/collectionasserthelper/
---
## CollectionAssertHelper struct

API Heler per operazioni relative alle collezioni.

```cpp
class CollectionAssertHelper
```

## Metodi

| Method | Description |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Verifica che tutti gli elementi della collezione soddisfino il predicato. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Verifica che almeno un elemento della collezione soddisfi il predicato. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serializza due collezioni per la rappresentazione del messaggio. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Converte la collezione in una stringa unendo le rappresentazioni testuali degli elementi. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Calcola la 'diff' tra due collezioni. Per ogni elemento di ciascuna collezione, come chiave, il valore risultante sarà positivo se l'elemento compare più volte nella collezione "expected", negativo se l'elemento compare più volte nella collezione "actual", e zero se l'elemento compare lo stesso numero di volte in entrambe le collezioni. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formatta la stringa da utilizzare come testo del messaggio. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)