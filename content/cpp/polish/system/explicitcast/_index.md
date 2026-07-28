---
title: ExplicitCast()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane, gdy typy źródłowy i wynikowy są takie same.
type: docs
weight: 2627
url: /pl/system/explicitcast/
---
## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane, gdy typy źródłowy i wynikowy są takie same.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane, gdy potrzebne jest proste rzutowanie podobne do konstruktora.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane dla opakowań wyjątków.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do rzutowania obiektu na wyjątk.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane, gdy zarówno źródło, jak i wynik są inteligentnymi wskaźnikami (bez explicite SmartPtr<...> w typie wyniku).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(Source) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane przy rzutowaniu surowego wskaźnika na inteligentny wskaźnik.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | Source | [Object](../object/) do rzutowania. |

### Wartość zwracana

Wynik rzutowania.

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane, gdy zarówno źródło, jak i wynik są inteligentnymi wskaźnikami (z explicite SmartPtr<...> w typie wyniku).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do rozpakowywania obiektu do nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do opakowywania nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do rozpakowywania nullable obiektu.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do opakowywania enumeracji.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do kopiowania typów wartościowych na stertę, gdy typ wartościowy powinien być referencjonowany jako inteligentny wskaźnik (w generykach ograniczonych typem interfejsu, ale specjalizowanych strukturą implementującą ten interfejs).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do uzyskiwania interfejsów z typów wartościowych.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do typowego opakowywania.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do opakowywania [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do rozpakowywania interfejsów.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do typowego rozpakowywania.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do rzutowania nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

## System::ExplicitCast(const Source\&) function

Rzutuje typ źródłowy na typ wynikowy przy użyciu rzutowania jawnego. Używane do rzutowania między tablicami.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

## Zobacz też

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)