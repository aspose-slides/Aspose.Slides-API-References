---
title: Cast()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de pointer naar zijn eigen type.
type: docs
weight: 287
url: /nl/system/smartptr/cast/
---
## SmartPtr::Cast() const methode

Converteert de pointer naar zijn eigen type.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Doeltype van het aangewezen object. |
| Check | Vlaggen om een uitzondering te gooien als er geen cast beschikbaar is. |

### Retourwaarde

Pointer van het gewijzigde type die altijd in gedeelde modus is.

## SmartPtr::Cast() const methode

Converteert de pointer naar het basistype met static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Doeltype van het aangewezen object. |
| Check | Vlaggen om een uitzondering te gooien als er geen cast beschikbaar is. |

### Retourwaarde

Pointer van het gewijzigde type die altijd in gedeelde modus is.

## SmartPtr::Cast() const methode

Converteert de pointer naar het afgeleide type met dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Doeltype van het aangewezen object. |
| Check | Vlaggen om een uitzondering te gooien als er geen cast beschikbaar is. |

### Retourwaarde

Pointer van het gewijzigde type die altijd in gedeelde modus is. Gooit InvalidCastException als er geen conversie beschikbaar is.

## SmartPtr::Cast() const methode

Converteert de pointer naar het afgeleide type met dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Doeltype van het aangewezen object. |
| Check | Vlaggen om een uitzondering te gooien als er geen cast beschikbaar is. |

### Retourwaarde

Pointer van het gewijzigde type die altijd in gedeelde modus is. Retourneert nullptr als er geen conversie beschikbaar is.

## Zie ook

* Klasse [SmartPtr](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)