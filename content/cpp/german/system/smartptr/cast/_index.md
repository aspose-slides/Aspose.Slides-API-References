---
title: Cast()
second_title: Aspose.Slides für C++ API-Referenz
description: Wandelt den Zeiger in seinen eigenen Typ um.
type: docs
weight: 287
url: /de/system/smartptr/cast/
---
## SmartPtr::Cast() const Methode

Wandelt den Zeiger in seinen eigenen Typ um.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Zieltyp des referenzierten Objekts. |
| Check | Flags, um eine Ausnahme zu werfen, wenn kein Cast verfügbar ist. |

### Rückgabewert

Zeiger des geänderten Typs, der immer im Shared-Modus ist.

## SmartPtr::Cast() const Methode

Wandelt den Zeiger in den Basistyp mittels static_cast um.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Zieltyp des referenzierten Objekts. |
| Check | Flags, um eine Ausnahme zu werfen, wenn kein Cast verfügbar ist. |

### Rückgabewert

Zeiger des geänderten Typs, der immer im Shared-Modus ist.

## SmartPtr::Cast() const Methode

Wandelt den Zeiger in den abgeleiteten Typ mittels dynamic_cast um.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Zieltyp des referenzierten Objekts. |
| Check | Flags, um eine Ausnahme zu werfen, wenn kein Cast verfügbar ist. |

### Rückgabewert

Zeiger des geänderten Typs, der immer im Shared-Modus ist. Wirft InvalidCastException, wenn keine Konvertierung verfügbar ist.

## SmartPtr::Cast() const Methode

Wandelt den Zeiger in den abgeleiteten Typ mittels dynamic_cast um.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Zieltyp des referenzierten Objekts. |
| Check | Flags, um eine Ausnahme zu werfen, wenn kein Cast verfügbar ist. |

### Rückgabewert

Zeiger des geänderten Typs, der immer im Shared-Modus ist. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## Siehe auch

* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)