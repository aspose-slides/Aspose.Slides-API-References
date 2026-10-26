---
title: cend()
second_title: Riferimento API di Aspose.Slides per C++
description: Accessor per il metodo cend() di una collezione sottostante. Viene compilato solo se SmartPtr_ è un tipo di specializzazione con il metodo cend().
type: docs
weight: 417
url: /it/system/smartptr/cend/
---
## SmartPtr::cend() const metodo

Accessor per il metodo [cend()](./) di una collezione sottostante. Viene compilato solo se SmartPtr_ è un tipo specializzazione con il metodo [cend()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### Valore restituito

iteratore alla fine della collezione

## Vedi anche

* Classe [SmartPtr](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)