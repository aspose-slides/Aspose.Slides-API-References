---
title: IsDefined()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda je zadaná hodnota členem typu výčtu E.
type: docs
weight: 27
url: /cs/system/enum/isdefined/
---
## Enum::IsDefined(E) metoda


Určuje, zda je zadaná hodnota členem typu výčtu **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | E | Hodnota, která se má zkontrolovat |

### Návratová hodnota

True, pokud je **value** členem výčtu **E**, jinak - false

## Enum::IsDefined(T) metoda


Určuje, zda je zadaná hodnota členem typu výčtu **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T | Hodnota, která se má zkontrolovat |

### Návratová hodnota

True, pokud je **value** členem výčtu **T**, jinak - false

## Enum::IsDefined(const String\&) metoda


Určuje, zda je hodnota se zadaným názvem mezi členy výčtu **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../string/)\& | Název, který se má zkontrolovat |

### Návratová hodnota

True, pokud existuje člen výčtu **E** se zadaným názvem.

## Viz také

* Typedef [UnderlyingType](../underlyingtype/)
* Třída [String](../../string/)
* Struktura [Enum](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)