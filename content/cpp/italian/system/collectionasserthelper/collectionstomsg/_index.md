---
title: CollectionsToMsg()
second_title: Riferimento API di Aspose.Slides per C++
description: Serializza due collezioni per la rappresentazione del messaggio.
type: docs
weight: 53
url: /it/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metodo

Serializza due collezioni per la rappresentazione del messaggio.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo di elemento della collezione previsto. |
| T2 | Tipo di elemento della collezione reale. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Una stringa personalizzata che viene inserita prima del valore previsto nel messaggio risultante |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Collezione prevista. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Collezione reale. |

### Valore di ritorno

Messaggio di facile lettura sul contenuto delle collezioni.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struttura [CollectionAssertHelper](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)