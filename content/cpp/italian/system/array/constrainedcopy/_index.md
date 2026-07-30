---
title: ConstrainedCopy()
second_title: Riferimento API di Aspose.Slides per C++
description: Copia un intervallo di elementi da un System.Array a partire dalla sorgente specificata.
type: docs
weight: 716
url: /it/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) metodo

Copia un intervallo di elementi da un [System.Array](../) a partire dalla sorgente specificata.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| SrcType | Tipo di elementi nell'array di origine |
| DstType | Tipo di elementi nell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array di origine |
| srcIndex | **int64_t** | [Index](../../index/) nell'array di origine che indica l'inizio dell'intervallo di elementi da copiare |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array di destinazione |
| dstIndex | **int64_t** | [Index](../../index/) nell'array di destinazione per iniziare a inserire gli elementi copiati |
| count | **int64_t** | Il numero di elementi da copiare |

## Osservazioni

IMPLEMENTAZIONE RAW TEMPORANEA SENZA NESSUNA CORREZIONE!

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)