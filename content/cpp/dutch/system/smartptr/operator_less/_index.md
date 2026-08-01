---
title: operator<()
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt minder-vergelijkingssemantiek voor de SmartPtr-klasse.
type: docs
weight: 235
url: /nl/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const methode

Biedt minder-vergelijkingssemantiek voor [SmartPtr](../) klasse.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Type van pointer om te vergelijken met de huidige. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | Y * | Pointer om te vergelijken met de huidige. |

### Retourwaarde

True als het object waarnaar verwezen wordt door [SmartPtr](../) 'less' is dan p en false anders.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const methode

Biedt minder-vergelijkingssemantiek voor [SmartPtr](../) klasse.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Type van pointer om te vergelijken met de huidige. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Pointer om te vergelijken met de huidige. |

### Retourwaarde

True als het object waarnaar verwezen wordt door [SmartPtr](../) 'less' is dan x en false anders.

## Zie ook

* Klasse [SmartPtr](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)