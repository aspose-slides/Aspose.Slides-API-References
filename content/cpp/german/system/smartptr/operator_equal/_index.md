---
title: operator=()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt eine Move-Zuweisung des SmartPtr-Objekts durch. x wird unbrauchbar.
type: docs
weight: 27
url: /de/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) Methode

Führt eine Move-Zuweisung des [SmartPtr](../) Objekts durch. x wird unbrauchbar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move-assign. |

### Rückgabewert

Referenz auf dieses Objekt.

## SmartPtr::operator=(const SmartPtr_&) Methode

Führt eine Kopierzuweisung des [SmartPtr](../) Objekts durch.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointer to copy-assign. |

### Rückgabewert

Referenz auf dieses Objekt.

## SmartPtr::operator=(const SmartPtr<Q>&) Methode

Führt eine Kopierzuweisung des [SmartPtr](../) Objekts durch. Führt erforderliche Typkonvertierungen durch.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Type of object pointed by x. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy-assign. |

### Rückgabewert

Referenz auf dieses Objekt.

## SmartPtr::operator=(Pointee_ *) Methode

Weist einen rohen Zeiger dem [SmartPtr](../) Objekt zu.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Pointer value to assign. |

### Rückgabewert

Referenz auf dieses Objekt.

## SmartPtr::operator=(std::nullptr_t) Methode

Setzt den Zeigerwert auf nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Rückgabewert

Referenz auf dieses Objekt.

## Siehe auch

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)