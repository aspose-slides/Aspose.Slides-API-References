---
title: With()
second_title: Riferimento API di Aspose.Slides per C++
description: Clona il record di riferimento e applica il functor di inizializzazione ad esso.
type: docs
weight: 2614
url: /it/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) funzione

Clona il record di riferimento e applica il functor di inizializzazione ad esso.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di record da clonare. |
| A | Tipo di functor di inizializzazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Puntatore condiviso all'oggetto da clonare e inizializzare. |
| initializer | const A\& | Functor di inizializzazione applicato al clone del record. |

### Valore restituito

Puntatore condiviso al record clonato.

## System::With(const T\&, const A\&) funzione

Copia il record struct e applica il functor di inizializzazione ad esso.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di record da copiare. |
| A | Tipo di functor di inizializzazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| record | const T\& | Record da copiare e inizializzare. |
| initializer | const A\& | Functor di inizializzazione applicato alla copia del record. |

### Valore restituito

Record copiato.

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)