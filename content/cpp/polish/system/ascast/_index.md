---
title: AsCast()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem 'as'. Używane, gdy potrzebny jest prosty rzut w stylu konstruktora.
type: docs
weight: 2640
url: /pl/system/ascast/
---
## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane, gdy potrzebny jest prosty rzut konstruktorowy.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane, gdy typy źródłowy i wynikowy są takie same.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane dla opakowań wyjątków.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania. Zwraca `nullptr`, jeśli konwersja nie jest dostępna.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do rzutowania obiektu na wyjątek.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania. Zwraca `nullptr`, jeśli konwersja nie jest dostępna.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane, gdy zarówno źródło, jak i wynik są inteligentnymi wskaźnikami.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania. Zwraca `nullptr`, jeśli konwersja nie jest dostępna.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane, gdy zarówno źródło, jak i wynik są inteligentnymi wskaźnikami (z explicite `SmartPtr<...>` w typie wyniku).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania. Zwraca `nullptr`, jeśli konwersja nie jest dostępna.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do odpakowywania obiektu do nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania. Zwraca pusty nullable, jeśli konwersja nie jest dostępna.

## System::AsCast(const Source\&) funkcja


Nieprawidłowe odpakowywanie do typu nie-obiektowego.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Zawsze zwraca `null`.

## System::AsCast(const Source\&) funkcja


Nieprawidłowe odpakowywanie do typu nie-obiektowego.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Zawsze zwraca `null`.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do opakowywania nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do opakowywania zwykłego obiektu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do opakowywania zwykłego obiektu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do odpakowywania stringa.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do rzutowania `nullptr`.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::AsCast(const Source\&) funkcja


Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania operatorem `as`. Używane do rzutowania pomiędzy tablicami.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania. Zwraca `nullptr`, jeśli brak konwersji dla dowolnego elementu tablicy.

## Zobacz także

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)