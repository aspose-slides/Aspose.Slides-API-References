---
title: end()
second_title: Aspose.Slides für C++ API-Referenz
description: Zugriff auf die end()-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der end()-Methode ist.
type: docs
weight: 391
url: /de/system/smartptr/end/
---
## SmartPtr::end() Methode

Zugriff auf die [end()](./)-Methode einer unterliegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](./)-Methode ist.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### Rückgabewert

iterator zum Ende der Sammlung

## SmartPtr::end() const Methode

Zugriff auf die [end()](./)-Methode einer unterliegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](./)-Methode ist.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### Rückgabewert

iterator zum Ende der Sammlung

## Siehe auch

* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)