---
title: ReferenceEquals()
second_title: Aspose.Slides for C++ - Dokumentacja API
description: "Specjalizacja Object::ReferenceEquals dla przypadku string i nullptr."
type: docs
weight: 261
url: /pl/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) metoda

Specjalizacja [Object::ReferenceEquals](./) dla przypadku String i nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) do porównania z nullptr. |

### Wartość zwracana

true, jeśli String jest null, false w przeciwnym razie.

## Object::ReferenceEquals(String const\&, String const\&) metoda

Specjalizacja [Object::ReferenceEquals](./) dla przypadku String.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Pierwszy String do porównania. |
| str2 | [String](../../string/) const\& | Drugi String do porównania. |

### Wartość zwracana

true, jeśli strings pasują, false w przeciwnym razie.

## Object::ReferenceEquals(ptr const\&, ptr const\&) metoda

Porównuje obiekty przez referencję.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Pierwszy wskaźnik do porównania. |
| objB | [ptr](../ptr/) const\& | Drugi wskaźnik do porównania. |

### Wartość zwracana

True, jeśli wskaźniki są zgodne i false w przeciwnym razie.

## Object::ReferenceEquals(T const\&, T const\&) metoda

Porównuje obiekty przez referencję.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektów do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| objA | T const\& | Pierwszy obiekt do porównania. |
| objB | T const\& | Drugi obiekt do porównania. |

### Wartość zwracana

True, jeśli adresy obiektów są zgodne i false w przeciwnym razie.

## Object::ReferenceEquals(T const\&, std::nullptr_t) metoda

Porównuje referencyjnie obiekt typu wartości z nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| objA | T const\& | Pierwszy obiekt do porównania. |

### Wartość zwracana

Zawsze zwraca false, ponieważ typy wartości nie mogą być nullowane.

## Zobacz także

* Definicja typu [ptr](../ptr/)
* Klasa [String](../../string/)
* Klasa [Object](../)
* Struktura [IsSmartPtr](../../issmartptr/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)