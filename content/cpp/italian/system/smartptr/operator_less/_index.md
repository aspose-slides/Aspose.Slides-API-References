---
title: operator<()
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce la semantica di confronto minore per la classe SmartPtr.
type: docs
weight: 235
url: /it/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method


Fornisce la semantica di confronto minore per la classe [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Y | Tipo di puntatore da confrontare con quello corrente. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | Y * | Puntatore da confrontare con quello corrente. |

### Valore di ritorno

True se l'oggetto a cui fa riferimento [SmartPtr](../) è 'less' rispetto a p e false altrimenti.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Fornisce la semantica di confronto minore per la classe [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Y | Tipo di puntatore da confrontare con quello corrente. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Puntatore da confrontare con quello corrente. |

### Valore di ritorno

True se l'oggetto a cui fa riferimento [SmartPtr](../) è 'less' rispetto a x e false altrimenti.

## Vedi anche

* Classe [SmartPtr](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)