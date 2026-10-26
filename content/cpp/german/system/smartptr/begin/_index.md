---
title: begin()
second_title: Aspose.Slides für C++ API-Referenz
description: Zugriffsfunktion für die begin() Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialtyp mit der begin() Methode ist.
type: docs
weight: 378
url: /de/system/smartptr/begin/
---
## SmartPtr::begin() Methode

Zugriffsfunktion für die [begin()](./) Methode einer unterliegenden Sammlung. Nur kompilierbar, wenn SmartPtr_ ein Spezialtyp mit der [begin()](./) Methode ist.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### Rückgabewert

iterator zum Anfang der Sammlung

## SmartPtr::begin() const Methode

Zugriffsfunktion für die [begin()](./) Methode einer unterliegenden Sammlung. Nur kompilierbar, wenn SmartPtr_ ein Spezialtyp mit der [begin()](./) Methode ist.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### Rückgabewert

iterator zum Anfang der Sammlung

## Siehe auch

* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)