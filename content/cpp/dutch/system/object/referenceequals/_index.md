---
title: ReferenceEquals()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specialisatie van Object::ReferenceEquals voor het geval van een string en nullptr."
type: docs
weight: 261
url: /nl/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) methode


Specialisatie van [Object::ReferenceEquals](./) voor het geval van een string en nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) om te vergelijken met nullptr. |

### Retourwaarde

true als de string null is, false anders.

## Object::ReferenceEquals(String const\&, String const\&) methode


Specialisatie van [Object::ReferenceEquals](./) voor het geval van strings.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Eerste string om te vergelijken. |
| str2 | [String](../../string/) const\& | Tweede string om te vergelijken. |

### Retourwaarde

true als strings overeenkomen, false anders.

## Object::ReferenceEquals(ptr const\&, ptr const\&) methode


Vergelijkt objecten op referentie.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Eerste pointer om te vergelijken. |
| objB | [ptr](../ptr/) const\& | Tweede pointer om te vergelijken. |

### Retourwaarde

True als de pointers overeenkomen en false anders.

## Object::ReferenceEquals(T const\&, T const\&) methode


Vergelijkt objecten op referentie.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van de te vergelijken objecten. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objA | T const\& | Eerste object om te vergelijken. |
| objB | T const\& | Tweede object om te vergelijken. |

### Retourwaarde

True als objectadressen overeenkomen en false anders.

## Object::ReferenceEquals(T const\&, std::nullptr_t) methode


Referentie vergelijkt een waarde-typen object met nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van het te vergelijken object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objA | T const\& | Eerste object om te vergelijken. |

### Retourwaarde

Geeft altijd false terug omdat waarde-typen niet geleegd kunnen worden.

## Zie ook

* Typedef [ptr](../ptr/)
* Klasse [String](../../string/)
* Klasse [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)