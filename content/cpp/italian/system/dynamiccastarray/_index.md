---
title: DynamicCastArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue il casting degli elementi dell'array specificato a un tipo diverso.
type: docs
weight: 2991
url: /it/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) funzione

Esegue il casting degli elementi dell'array specificato a un tipo diverso.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| To | Il tipo a cui castare gli elementi dell'array specificato |
| From | Il tipo degli elementi dell'array di cui fare il cast |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Puntatore condiviso all'array contenente gli elementi da castare |

### Valore restituito

Un puntatore a un nuovo array contenente elementi di tipo **To** equivalenti agli elementi di **from**

Deprecata
:   Aggiunta per compatibilità retroattiva. Usa ExplicitCast invece.

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Classe [Array](../array/)
* Spazio dei nomi [System](../)
* Library [Aspose.Slides](../../)