---
title: IsProperSupersetOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se il set corrente è un superset rigoroso di un altro contenitore.
type: docs
weight: 53
url: /it/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) metodo

Verifica se il set corrente è un superset rigoroso dell'altro contenitore.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | Sottoinsieme da verificare. |

### Valore di ritorno

Vero se tutti gli elementi in **other** sono presenti nel set e il set ha più elementi rispetto a **other**, falso altrimenti.

## Vedi anche

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Classe [ISet](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)