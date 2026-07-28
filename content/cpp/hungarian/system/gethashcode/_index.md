---
title: GetHashCode()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy hash kódot a megadott skalárértékhez.
type: docs
weight: 2484
url: /hu/system/gethashcode/
---
## System::GetHashCode(const T&) függvény

Visszaad egy hash kódot a megadott skalárértékhez.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A típus, amely értékhez a függvény hash kódot generál |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T& | Az érték, amelyhez hash kódot generálunk |

### Visszatérési érték

A megadott értékhez generált hash kód

## System::GetHashCode(const T&) függvény

Visszaad egy hash kódot a megadott objektumhoz.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A típus, amely objektumhoz a függvény hash kódot generál |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T& | A [SmartPtr](../smartptr/) amely az objektumra mutat, amelyhez hash kódot generálunk |

### Visszatérési érték

A megadott objektumhoz generált hash kód

## System::GetHashCode(const T&) függvény

Visszaad egy hash kódot a megadott objektumhoz, amely egy kivétel.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A típus, amely objektumhoz a függvény hash kódot generál |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T& | Az Exception Wrapper, amely az objektumot tartalmazza, amelyhez hash kódot generálunk |

### Visszatérési érték

A megadott objektumhoz generált hash kód

## System::GetHashCode(const T&) függvény

Visszaad egy hash kódot a megadott objektumhoz, amely nem intelligens mutató és nem kivétel.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A típus, amely objektumhoz a függvény hash kódot generál |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T& | A const referencia az objektumra, amelyhez hash kódot generálunk |

### Visszatérési érték

A megadott objektumhoz generált hash kód

## System::GetHashCode(const std::thread::id&) függvény

Specializáció a std::thread::id számára; Visszaadja a hash kódot a megadott szálobjektumhoz.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Lásd még

* Struktúra [IsSmartPtr](../issmartptr/)
* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)