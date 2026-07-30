---
title: MakeDiff()
second_title: Aspose.Slides per il Riferimento API di C++
description: Calcola la 'diff' tra due collezioni. Per ogni elemento di ciascuna collezione, il valore risultante sarà positivo se l'elemento compare più volte nella collezione \"expected\", negativo se l'elemento compare più volte nella collezione \"actual\", e zero se l'elemento compare lo stesso numero di volte in entrambe le collezioni.
type: docs
weight: 1
url: /it/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metodo

Calcola la 'diff' tra due collezioni. Per ogni elemento di ciascuna collezione, il valore risultante sarà positivo se l'elemento compare più volte nella collezione "expected", negativo se l'elemento compare più volte nella collezione "actual", e zero se l'elemento compare lo stesso numero di volte in entrambe le collezioni.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| T1 | Tipo di elemento della collezione expected. |
| T2 | Tipo di elemento della collezione actual. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Collezione expected. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Collezione actual. |

### Valore di ritorno

Mappa dei risultati del confronto per valore secondo le regole sopra.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Dictionary](../../../system.collections.generic/dictionary/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)