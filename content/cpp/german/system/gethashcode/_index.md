---
title: GetHashCode()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Hashcode für den angegebenen skalaren Wert zurück.
type: docs
weight: 2484
url: /de/system/gethashcode/
---
## System::GetHashCode(const T&) Funktion

Gibt einen Hashcode für den angegebenen skalaren Wert zurück.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Wertes, für den die Funktion einen Hashcode erzeugt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T& | Der Wert, für den ein Hashcode erzeugt werden soll |

### Rückgabewert

Der für den angegebenen Wert erzeugte Hashcode

## System::GetHashCode(const T&) Funktion

Gibt einen Hashcode für das angegebene Objekt zurück.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Objekts, für das die Funktion einen Hashcode erzeugt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T& | Der [SmartPtr](../smartptr/), der auf das Objekt zeigt, für das ein Hashcode erzeugt werden soll |

### Rückgabewert

Der für das angegebene Objekt erzeugte Hashcode

## System::GetHashCode(const T&) Funktion

Gibt einen Hashcode für das angegebene Objekt zurück, das eine Ausnahme ist.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Objekts, für das die Funktion einen Hashcode erzeugt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T& | Der Exception Wrapper, der das Objekt enthält, für das ein Hashcode erzeugt werden soll |

### Rückgabewert

Der für das angegebene Objekt erzeugte Hashcode

## System::GetHashCode(const T&) Funktion

Gibt einen Hashcode für das angegebene Objekt zurück, das weder ein Smart Pointer noch eine Ausnahme ist.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des Objekts, für das die Funktion einen Hashcode erzeugt |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T& | Eine konstante Referenz auf das Objekt, für das ein Hashcode erzeugt werden soll |

### Rückgabewert

Der für das angegebene Objekt erzeugte Hashcode

## System::GetHashCode(const std::thread::id&) Funktion

Spezialisierung für std::thread::id; Gibt den Hashcode für das angegebene Thread-Objekt zurück.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Siehe auch

* Struktur [IsSmartPtr](../issmartptr/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)