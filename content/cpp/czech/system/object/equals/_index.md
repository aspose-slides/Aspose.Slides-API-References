---
title: Equals()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává objekty pomocí semantiky C# Object.Equals.
type: docs
weight: 157
url: /cs/system/object/equals/
---
## Object::Equals(ptr) metoda


Porovnává objekty pomocí semantiky C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) pro porovnání aktuálního. |

### Návratová hodnota

True, pokud jsou objekty považovány za rovné, a false jinak.

## Object::Equals(T1 const\&, T2 const\&) metoda


Porovnává objekty referenčního typu ve stylu C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ prvního objektu k porovnání. |
| T2 | Typ druhého objektu k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| objA | T1 const\& | První objekt k porovnání. |
| objB | T2 const\& | Druhý objekt k porovnání. |

### Návratová hodnota

True, pokud objekty odpovídají buď referencí, nebo sémanticky (pomocí [Object.Equals](./)-podobného porovnání), false jinak.

## Object::Equals(T1 const\&, T2 const\&) metoda


Porovnává objekty hodnotového typu ve stylu C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | Typ prvního objektu k porovnání. |
| T2 | Typ druhého objektu k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| objA | T1 const\& | První objekt k porovnání. |
| objB | T2 const\& | Druhý objekt k porovnání. |

### Návratová hodnota

True, pokud jsou objekty považovány za rovné pomocí dostupného operátoru rovnosti, false jinak.

## Object::Equals(float const\&, float const\&) metoda


Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| objA | **float** const\& | Hodnota plovoucí desetinné čárky na levé straně. |
| objB | **float** const\& | Hodnota plovoucí desetinné čárky na pravé straně. |

### Návratová hodnota

True, pokud **objA** a **objB** jsou oba NaN nebo rovné, false jinak.

## Object::Equals(double const\&, double const\&) metoda


Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| objA | **double** const\& | Hodnota dvojité přesnosti na levé straně. |
| objB | **double** const\& | Hodnota dvojité přesnosti na pravé straně. |

### Návratová hodnota

True, pokud **objA** a **objB** jsou oba NaN nebo rovné, false jinak.

## Viz také

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)