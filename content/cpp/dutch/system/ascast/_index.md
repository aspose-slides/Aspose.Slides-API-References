---
title: AsCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Cast de brontype naar het resulttype met behulp van de 'as' operator cast. Wordt gebruikt wanneer een eenvoudige constructor-achtige cast nodig is.
type: docs
weight: 2640
url: /nl/system/ascast/
---
## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt wanneer een eenvoudige constructor-achtige cast nodig is.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt wanneer de bron- en resulttypen hetzelfde zijn.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt voor uitzonderingswrappers.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat. Retourneert nullptr als er geen conversie beschikbaar is.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt om een object naar een uitzondering te casten.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat. Retourneert nullptr als er geen conversie beschikbaar is.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt wanneer zowel de bron als het result slimme pointers zijn.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat. Retourneert nullptr als er geen conversie beschikbaar is.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt wanneer zowel de bron als het result slimme pointers zijn (met expliciete SmartPtr<...> in het resulttype).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat. Retourneert nullptr als er geen conversie beschikbaar is.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt voor het unboxen van een object naar een nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat. Retourneert een lege nullable als er geen conversie beschikbaar is.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Ongeldige unboxing naar een niet-objecttype.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Retourneert altijd null.

## System::AsCast(const Source\&) functie

Ongeldige unboxing naar een niet-objecttype.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Retourneert altijd null.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt voor het boxen van een nullable-object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt voor het boxen van een algemeen object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt voor het boxen van een algemeen object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt voor string-unboxing.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt voor nullptr-casting.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat.

## System::AsCast(const Source\&) functie

Cast de brontype naar het resulttype met behulp van de ‘as’ operator cast. Wordt gebruikt om te casten tussen arrays.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) om te casten. |

### Retourwaarde

Het castresultaat. Retourneert nullptr als er geen conversie voor een array-element beschikbaar is.

## Zie ook

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)