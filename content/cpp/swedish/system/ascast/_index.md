---
title: AsCast()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar källtypen till resultattypen med 'as'-operatorns kast. Används när en enkel konstruktorliknande konvertering behövs.
type: docs
weight: 2640
url: /sv/system/ascast/
---
## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används när en enkel konstruktorliknande konvertering behövs.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används när käll- och resultattyperna är desamma.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för undantagsomslag.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen. Returnerar nullptr om ingen konvertering är tillgänglig.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för att konvertera objekt till undantag.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen. Returnerar nullptr om ingen konvertering är tillgänglig.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används när både käll- och resultattyp är smarta pekare.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen. Returnerar nullptr om ingen konvertering är tillgänglig.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används när både käll- och resultattyp är smarta pekare (med explicit SmartPtr<...> i resultattypen).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen. Returnerar nullptr om ingen konvertering är tillgänglig.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för att avpaketera objekt till nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen. Returnerar tomt nullable om ingen konvertering är tillgänglig.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Ogiltig avpaketering till icke-objekttyp.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Returnerar alltid null.

## System::AsCast(const Source\&) funktion


Ogiltig avpaketering till icke-objekttyp.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Returnerar alltid null.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för att paketera nullable-objekt.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för att paketera vanligt objekt.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för att paketera vanligt objekt.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för avpaketering av string.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för nullptr-konvertering.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen.

## System::AsCast(const Source\&) funktion


Konverterar källtypen till resultattypen med 'as'-operatorn. Används för konvertering mellan arrayer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) att konvertera. |

### Returvärde

Resultatet av konverteringen. Returnerar nullptr om ingen konvertering för någon arraymedlem är tillgänglig.

## Se även

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)