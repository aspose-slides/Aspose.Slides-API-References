---
title: cend()
second_title: Aspose.Slides für C++ API-Referenz
description: Zugriffsmethode für die cend()-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der cend()-Methode ist.
type: docs
weight: 417
url: /de/system/smartptr/cend/
---
## SmartPtr::cend() const Methode

Zugriffsmethode für die [cend()](./)-Methode einer unterliegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](./)-Methode ist.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### Rückgabewert

iterator zum Ende der Sammlung

## Siehe auch

* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)