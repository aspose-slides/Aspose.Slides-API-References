---
title: begin()
second_title: Aspose.Slides voor C++ API-referentie
description: Accessor voor de begin() methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met de begin() methode.
type: docs
weight: 378
url: /nl/system/smartptr/begin/
---
## SmartPtr::begin() methode

Accessor voor [begin()](./)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](./)-methode.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### Retourwaarde

iterator naar het begin van de collectie

## SmartPtr::begin() const methode

Accessor voor [begin()](./)-methode van een onderliggende collectie. Compileert alleen als SmartPtr_ een specialisatietype is met [begin()](./)-methode.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### Retourwaarde

iterator naar het begin van de collectie

## Zie ook

* Klasse [SmartPtr](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)