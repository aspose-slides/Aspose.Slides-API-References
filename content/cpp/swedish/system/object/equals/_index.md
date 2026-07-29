---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: Jämför objekt med C# Object.Equals-semantik.
type: docs
weight: 157
url: /sv/system/object/equals/
---
## Object::Equals(ptr) metod


Jämför objekt med C# [Object.Equals](./) semantik.

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) för att jämföra den aktuella med. |

### Returvärde

Sant om objekt anses vara lika och falskt annars.

## Object::Equals(T1 const\&, T2 const\&) metod


Jämför referenstyp-objekt i C#-stil.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av första objektet att jämföra. |
| T2 | Typ av andra objektet att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T1 const\& | Första objektet att jämföra. |
| objB | T2 const\& | Andra objektet att jämföra. |

### Returvärde

Sant om objekt matchar antingen genom referens eller semantiskt (genom [Object.Equals](./)-liknande jämförelse), falskt annars.

## Object::Equals(T1 const\&, T2 const\&) metod


Jämför värdetyp-objekt i C#-stil.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ av första objektet att jämföra. |
| T2 | Typ av andra objektet att jämföra. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | T1 const\& | Första objektet att jämföra. |
| objB | T2 const\& | Andra objektet att jämföra. |

### Returvärde

Sant om objekt anses lika med tillgänglig likhetsoperator, falskt annars.

## Object::Equals(float const\&, float const\&) metod


Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | **float** const\& | Vänster (LHS) flyttalsvärde. |
| objB | **float** const\& | Höger (RHS) flyttalsvärde. |

### Returvärde

Sant om **objA** och **objB** båda är NaN eller lika, falskt annars.

## Object::Equals(double const\&, double const\&) metod


Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objA | **double** const\& | Vänster (LHS) flyttalsvärde. |
| objB | **double** const\& | Höger (RHS) flyttalsvärde. |

### Returvärde

Sant om **objA** och **objB** båda är NaN eller lika, falskt annars.

## Se även

* Typedef [ptr](../ptr/)
* Klass [Object](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)