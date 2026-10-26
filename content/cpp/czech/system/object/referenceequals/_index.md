---
title: ReferenceEquals()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Specializace Object::ReferenceEquals pro případ string a nullptr."
type: docs
weight: 261
url: /cs/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) metoda

Specializace [Object::ReferenceEquals](./) pro případ String a nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) pro porovnání s nullptr. |

### Návratová hodnota

true, pokud je string null, false jinak.

## Object::ReferenceEquals(String const\&, String const\&) metoda

Specializace [Object::ReferenceEquals](./) pro případ String.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | První String pro porovnání. |
| str2 | [String](../../string/) const\& | Druhý String pro porovnání. |

### Návratová hodnota

true, pokud se Stringy shodují, false jinak.

## Object::ReferenceEquals(ptr const\&, ptr const\&) metoda

Porovnává objekty podle reference.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | První ukazatel pro porovnání. |
| objB | [ptr](../ptr/) const\& | Druhý ukazatel pro porovnání. |

### Návratová hodnota

True, pokud se ukazatele shodují, false jinak.

## Object::ReferenceEquals(T const\&, T const\&) metoda

Porovnává objekty podle reference.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektů k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| objA | T const\& | První objekt k porovnání. |
| objB | T const\& | Druhý objekt k porovnání. |

### Návratová hodnota

True, pokud se adresy objektů shodují, false jinak.

## Object::ReferenceEquals(T const\&, std::nullptr_t) metoda

Reference porovnává objekt hodnotového typu s nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| objA | T const\& | První objekt k porovnání. |

### Návratová hodnota

Vždy vrací false, protože hodnotové typy nelze nastavit na null.

## Viz také

* Typedef [ptr](../ptr/)
* Třída [String](../../string/)
* Třída [Object](../)
* Struktura [IsSmartPtr](../../issmartptr/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)