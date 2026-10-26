---
title: MakeObject()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een object op de heap en retourneert een gedeelde pointer hiernaar.
type: docs
weight: 2887
url: /nl/system/makeobject/
---
## System::MakeObject(Args\&&...) functie


Maakt een object op de heap en retourneert een gedeelde pointer hiernaar.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Klasse om te instantieren. |
| Args | Types van constructorargumenten. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | Args\&&... | Constructorargumenten. |

### Retourwaarde

[SmartPtr](../smartptr/) naar nieuw aangemaakt object, altijd in gedeelde modus.

## System::MakeObject(Args\&&...) functie


Maakt een object op de heap en retourneert een gedeelde pointer hiernaar.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [SmartPtr](../smartptr/) naar klasse om te instantieren. |
| Args | Types van constructorargumenten. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| args | Args\&&... | Constructorargumenten. |

### Retourwaarde

[SmartPtr](../smartptr/) naar nieuw aangemaakt object, altijd in gedeelde modus.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Struct [IsSmartPtr](../issmartptr/)
* Naamruimte [System](../)
* Library [Aspose.Slides](../../)