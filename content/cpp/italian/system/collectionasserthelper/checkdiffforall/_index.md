---
title: CheckDiffForAll()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica che tutti gli elementi della raccolta aderiscano al predicato.
type: docs
weight: 14
url: /it/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metodo

Verifica che tutti gli elementi della raccolta aderiscano al predicato.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicato da verificare. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valori da verificare. |

### Valore restituito

False se il controllo fallisce per qualche elemento, true se tutti passano.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)