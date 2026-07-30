---
title: begin()
second_title: Riferimento API Aspose.Slides per C++
description: Accessor per il metodo begin() di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo begin().
type: docs
weight: 378
url: /it/system/smartptr/begin/
---
## SmartPtr::begin() metodo

Accessor per il metodo [begin()](./) della collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzazione con il metodo [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### Valore di ritorno

iterator to the begin of collection

## SmartPtr::begin() const metodo

Accessor per il metodo [begin()](./) della collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzazione con il metodo [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### Valore di ritorno

iterator to the begin of collection

## Vedi anche

* Classe [SmartPtr](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)