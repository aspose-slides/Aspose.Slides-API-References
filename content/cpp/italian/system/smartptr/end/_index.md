---
title: end()
second_title: Riferimento API di Aspose.Slides per C++
description: Accessor per il metodo end() di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo end().
type: docs
weight: 391
url: /it/system/smartptr/end/
---
## SmartPtr::end() metodo


Accessor per il metodo [end()](./) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```


### Valore di ritorno

iteratore alla fine della collezione

## SmartPtr::end() const metodo


Accessor per il metodo [end()](./) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```


### Valore di ritorno

iteratore alla fine della collezione

## Vedi anche

* Classe [SmartPtr](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)