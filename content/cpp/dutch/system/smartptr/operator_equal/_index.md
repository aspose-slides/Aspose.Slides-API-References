---
title: operator=()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een move-toekenning uit op het SmartPtr-object. x wordt onbruikbaar.
type: docs
weight: 27
url: /nl/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) methode

Voert een move-toekenning uit op het [SmartPtr](../) object. x wordt onbruikbaar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Pointer naar move-toekenning. |

### Retourwaarde

Referentie naar dit object.

## SmartPtr::operator=(const SmartPtr_&) methode

Voert een copy-toekenning uit op het [SmartPtr](../) object.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Pointer naar copy-toekenning. |

### Retourwaarde

Referentie naar dit object.

## SmartPtr::operator=(const SmartPtr\<Q\>&) methode

Voert een copy-toekenning uit op het [SmartPtr](../) object. Voert de vereiste typeconversies uit.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Type van het object waar x naar wijst. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>& | Pointer naar copy-toekenning. |

### Retourwaarde

Referentie naar dit object.

## SmartPtr::operator=(Pointee_ *) methode

Ken een ruwe pointer toe aan het [SmartPtr](../) object.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Pointerwaarde om toe te wijzen. |

### Retourwaarde

Referentie naar dit object.

## SmartPtr::operator=(std::nullptr_t) methode

Stelt de pointerwaarde in op nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Retourwaarde

Referentie naar dit object.

## Zie ook

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Klasse [SmartPtr](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)