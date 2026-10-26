---
title: Equals()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Porównuje obiekty przy użyciu semantyki C# Object.Equals.
type: docs
weight: 157
url: /pl/system/object/equals/
---
## Object::Equals(ptr) metoda


Porównuje obiekty używając semantyki C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) do porównania z bieżącym. |

### Wartość zwracana

True if objects are considered equal and false otherwise.

## Object::Equals(T1 const\&, T2 const\&) metoda


Porównuje obiekty typu referencyjnego w stylu C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ pierwszego obiektu do porównania. |
| T2 | Typ drugiego obiektu do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| objA | T1 const\& | Pierwszy obiekt do porównania. |
| objB | T2 const\& | Drugi obiekt do porównania. |

### Wartość zwracana

True jeśli obiekty pasują zarówno przez referencję, jak i semantycznie (przez porównanie podobne do [Object.Equals](./)), false w przeciwnym razie.

## Object::Equals(T1 const\&, T2 const\&) metoda


Porównuje obiekty typu wartościowego w stylu C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Typ pierwszego obiektu do porównania. |
| T2 | Typ drugiego obiektu do porównania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| objA | T1 const\& | Pierwszy obiekt do porównania. |
| objB | T2 const\& | Drugi obiekt do porównania. |

### Wartość zwracana

True jeśli obiekty są uważane za równe przy użyciu dostępnego operatora równości, false w przeciwnym razie.

## Object::Equals(float const\&, float const\&) metoda


Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| objA | **float** const\& | Lewa wartość zmiennoprzecinkowa. |
| objB | **float** const\& | Prawa wartość zmiennoprzecinkowa. |

### Wartość zwracana

True jeśli **objA** i **objB** są oba NaN lub równe, false w przeciwnym razie.

## Object::Equals(double const\&, double const\&) metoda


Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| objA | **double** const\& | Lewa wartość zmiennoprzecinkowa. |
| objB | **double** const\& | Prawa wartość zmiennoprzecinkowa. |

### Wartość zwracana

True jeśli **objA** i **objB** są oba NaN lub równe, false w przeciwnym razie.

## Zobacz także

* Definicja typu [ptr](../ptr/)
* Klasa [Object](../)
* Struktura [IsSmartPtr](../../issmartptr/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)