---
title: cbegin()
second_title: Riferimento API di Aspose.Slides per C++
description: Accessor per il metodo cbegin() di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo cbegin().
type: docs
weight: 404
url: /it/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const metodo


Accessor per il metodo [cbegin()](./) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```


### Valore di ritorno

iteratore all'inizio della collezione

## Vedi anche

* Classe [SmartPtr](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)