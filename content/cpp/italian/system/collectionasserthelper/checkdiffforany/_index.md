---
title: CheckDiffForAny()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica che qualsiasi elemento della collezione soddisfi il predicato.
type: docs
weight: 27
url: /it/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metodo

Verifica che qualsiasi elemento della collezione soddisfi il predicato.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predicato da verificare. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Valori da verificare. |

### Valore di ritorno

True se la verifica ha successo per qualsiasi elemento, false se tutti superano.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ICollection](../../../system.collections.generic/icollection/)
* Struttura [CollectionAssertHelper](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)