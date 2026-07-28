---
title: ReferenceEquals()
second_title: Aspose.Slides a C++ API referenciához
description: "Az Object::ReferenceEquals specializációja string és nullptr esetére."
type: docs
weight: 261
url: /hu/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) metódus

A [Object::ReferenceEquals](./) specializációja string és nullptr esetére.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) a nullptr-hez való összehasonlításhoz. |

### Visszatérési érték

true, ha a string null, egyébként false.

## Object::ReferenceEquals(String const\&, String const&) metódus

A [Object::ReferenceEquals](./) specializációja stringek esetére.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Az első összehasonlítandó string. |
| str2 | [String](../../string/) const\& | A második összehasonlítandó string. |

### Visszatérési érték

true, ha a stringek egyeznek, egyébként false.

## Object::ReferenceEquals(ptr const\&, ptr const&) metódus

Objektumokat hasonlít össze referenciával.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Az első összehasonlítandó mutató. |
| objB | [ptr](../ptr/) const\& | A második összehasonlítandó mutató. |

### Visszatérési érték

True, ha a mutatók egyeznek, egyébként false.

## Object::ReferenceEquals(T const\&, T const&) metódus

Objektumokat hasonlít össze referenciával.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az összehasonlítandó objektumok típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| objA | T const\& | Az első összehasonlítandó objektum. |
| objB | T const\& | A második összehasonlítandó objektum. |

### Visszatérési érték

True, ha az objektumcímek egyeznek, egyébként false.

## Object::ReferenceEquals(T const\&, std::nullptr_t) metódus

Referencia-összehasonlítja az értéktípusú objektumot a nullptr-tel.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az összehasonlítandó objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| objA | T const\& | Az első összehasonlítandó objektum. |

### Visszatérési érték

Mindig false értéket ad vissza, mivel az értéktípusok nem lehetnek null értékűek.

## Lásd még

* Típusdefiníció [ptr](../ptr/)
* Osztály [String](../../string/)
* Osztály [Object](../)
* Struktúra [IsSmartPtr](../../issmartptr/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)