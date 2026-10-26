---
title: cbegin()
second_title: Aspose.Slides für C++ API-Referenz
description: Zugriffsmethode für die cbegin()-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der cbegin()-Methode ist.
type: docs
weight: 404
url: /de/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const Methode

Zugriffsmethode für die [cbegin()](./)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](./)-Methode ist.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Rückgabewert

Iterator zum Anfang der Sammlung

## Siehe auch

* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)