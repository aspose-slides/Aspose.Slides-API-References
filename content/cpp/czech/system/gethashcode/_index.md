---
title: GetHashCode()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací hash kód pro zadanou skalární hodnotu.
type: docs
weight: 2484
url: /cs/system/gethashcode/
---
## System::GetHashCode(const T\&) funkce


Vrátí hash kód pro zadanou skalární hodnotu.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty, pro kterou funkce generuje hash kód |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | Hodnota, pro kterou se generuje hash kód |

### Vrácená hodnota

Hash kód vygenerovaný pro zadanou hodnotu

## System::GetHashCode(const T\&) funkce


Vrátí hash kód pro zadaný objekt.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu, pro který funkce generuje hash kód |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../smartptr/) ukazující na objekt, pro který se generuje hash kód |

### Vrácená hodnota

Hash kód vygenerovaný pro zadaný objekt

## System::GetHashCode(const T\&) funkce


Vrátí hash kód pro zadaný objekt, který je výjimkou.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu, pro který funkce generuje hash kód |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | Exception Wrapper, který obsahuje objekt, pro který se generuje hash kód |

### Vrácená hodnota

Hash kód vygenerovaný pro zadaný objekt

## System::GetHashCode(const T\&) funkce


Vrátí hash kód pro zadaný objekt, který není chytrým ukazatelem ani výjimkou.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ objektu, pro který funkce generuje hash kód |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | const reference na objekt, pro který se generuje hash kód |

### Vrácená hodnota

Hash kód vygenerovaný pro zadaný objekt

## System::GetHashCode(const std::thread::id\&) funkce


Specializace pro std::thread::id; Vrací hash kód pro zadaný objekt vlákna.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Viz také

* Struktura [IsSmartPtr](../issmartptr/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Knihovna [Aspose.Slides](../../)