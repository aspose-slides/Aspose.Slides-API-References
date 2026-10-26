---
title: Equals()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt objecten met behulp van C# Object.Equals semantiek.
type: docs
weight: 157
url: /nl/system/object/equals/
---
## Object::Equals(ptr) methode


Vergelijkt objecten met behulp van C# [Object.Equals](./) semantiek.

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) om de huidige te vergelijken. |

### Retourwaarde

True als objecten als gelijk worden beschouwd en false anders.

## Object::Equals(T1 const\&, T2 const\&) methode


Vergelijkt referentietype-objecten in C# stijl.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Type van het eerste object om te vergelijken. |
| T2 | Type van het tweede object om te vergelijken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objA | T1 const\& | Eerste object om te vergelijken. |
| objB | T2 const\& | Tweede object om te vergelijken. |

### Retourwaarde

True als objecten overeenkomen door referentie of semantisch (door [Object.Equals](./)-achtige vergelijking), false anders.

## Object::Equals(T1 const\&, T2 const\&) methode


Vergelijkt waardetype-objecten in C# stijl.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Type van het eerste object om te vergelijken. |
| T2 | Type van het tweede object om te vergelijken. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objA | T1 const\& | Eerste object om te vergelijken. |
| objB | T2 const\& | Tweede object om te vergelijken. |

### Retourwaarde

True als objecten als gelijk worden beschouwd door de beschikbare gelijkheidsoperator, false anders.

## Object::Equals(float const\&, float const\&) methode


Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objA | **float** const\& | Linkerzijde zwevendekommagetal. |
| objB | **float** const\& | Rechterzijde zwevendekommagetal. |

### Retourwaarde

True als **objA** en **objB** beide NaN zijn of gelijk, false anders.

## Object::Equals(double const\&, double const\&) methode


Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objA | **double** const\& | Linkerzijde zwevendekommagetal. |
| objB | **double** const\& | Rechterzijde zwevendekommagetal. |

### Retourwaarde

True als **objA** en **objB** beide NaN zijn of gelijk, false anders.

## Zie ook

* Typedef [ptr](../ptr/)
* Klasse [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)