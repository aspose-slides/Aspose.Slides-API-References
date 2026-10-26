---
title: operator+()
second_title: Aspose.Slides C++ API referenciája
description: String összefűző operátor.
type: docs
weight: 274
url: /hu/system/string/operator_plus/
---
## String::operator+(const String\&) const metódus

[String](../) konkatenációs operátor.

```cpp
String System::String::operator+(const String &str) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) a jelenlegi végéhez hozzáadandó. |

### Visszatérési érték

Összefűzött karakterlánc.

## String::operator+(const T\&) const metódus

[String](../) konkatenáció string literállal vagy karakterlánc mutatóval.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Egyik a string literál vagy karakterlánc mutató formák közül. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arg | const T\& | Entitás a jelenlegi stringgel való konkatenáláshoz. |

### Visszatérési érték

Összefűzött karakterlánc.

## String::operator+(char_t) const metódus

```cpp
String System::String::operator+(char_t x) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | char_t | Karakter a hozzáadáshoz. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## String::operator+(int) const metódus

```cpp
String System::String::operator+(int i) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | int | Egész érték, amelyet stringgé alakítunk és hozzáadunk. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## String::operator+(uint32_t) const metódus

```cpp
String System::String::operator+(uint32_t i) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **uint32_t** | Érték, amelyet stringgé alakítunk és hozzáadunk. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## String::operator+(double) const metódus

```cpp
String System::String::operator+(double d) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| d | **double** | Érték, amelyet stringgé alakítunk és hozzáadunk. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## String::operator+(int64_t) const metódus

```cpp
String System::String::operator+(int64_t v) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| v | **int64_t** | Érték, amelyet stringgé alakítunk és hozzáadunk. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## String::operator+(const T\&) const metódus

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | mutató típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) a stringgé konvertálásra a [ToString()](../tostring/) hívással és a jelenlegi stringhez hozzáadandó. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## String::operator+(const T\&) const metódus

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus, amelyen a [ToString()](../tostring/) hívást végrehajtjuk. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) a stringgé konvertálásra a [ToString()](../tostring/) hívással és a jelenlegi stringhez hozzáadandó. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## String::operator+(T) const metódus

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus a stringgel való konkatenáláshoz. Bool |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) érték a stringgé konvertálásra és hozzáadásra. |

### Visszatérési érték

[String](../) konkatenáció eredménye.

## Lásd még

* Osztály [String](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)