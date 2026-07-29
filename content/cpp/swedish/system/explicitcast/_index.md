---
title: ExplicitCast()
second_title: Aspose.Slides för C++ API-referens
description: Kastar källtypen till resultattypen med explicit cast. Används när käll- och resultattyperna är desamma.
type: docs
weight: 2627
url: /sv/system/explicitcast/
---
## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används när käll- och resultattyperna är desamma.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används när en enkel konstruktorliknande cast behövs.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för undantagsomslag.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att kasta ett objekt till ett undantag.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används när både källan och resultatet är smarta pekare (utan explicit SmartPtr<...> i resultattypen).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(Source) funktion


Kastar källtypen till resultattypen med explicit cast. Används när en råpekare kastas till en smart pekare.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | Source | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används när både källan och resultatet är smarta pekare (med explicit SmartPtr<...> i resultattypen).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att avpaketera ett objekt till nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att paketera nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att avpaketera ett nullable-objekt.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för enum-paketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att kopiera värdetyper till heapen när värdetypen bör refereras som en smart pekare (i generiska typer begränsade med gränssnittstyp men specialiserade med struktur som implementerar detta gränssnitt).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att hämta gränssnitt från värdetyper.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för vanlig paketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för [System::String](../string/) paketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att avpaketera gränssnitt.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för vanlig avpaketering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för nullptr-cast.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## System::ExplicitCast(const Source&) funktion


Kastar källtypen till resultattypen med explicit cast. Används för att kasta mellan arrayer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source& | [Object](../object/) att kasta. |

### Returvärde

Resultatet av casten.

## Se även

* Typedef [Exception](../exception/)
* Klass [SmartPtr](../smartptr/)
* Klass [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namnrymd [System](../)
* Library [Aspose.Slides](../../)