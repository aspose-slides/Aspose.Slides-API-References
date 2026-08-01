---
title: ExplicitCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt wanneer het bron- en het resulttype hetzelfde zijn.
type: docs
weight: 2627
url: /nl/system/explicitcast/
---
## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt wanneer het bron- en het resulttype hetzelfde zijn.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt wanneer een eenvoudige constructor-achtige cast nodig is.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor exceptie-wrappers.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor het casten van een object naar een exceptie.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt wanneer zowel bron- als resulttype slimme pointers zijn (zonder expliciete SmartPtr<…> in het resulttype).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(Source) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt bij het casten van een ruwe pointer naar een slimme pointer.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Source | Het brontype. |
| Result | Het resulttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | Source | [Object](../object/) om te casten. |

### Retourwaarde

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt wanneer zowel bron- als resulttype slimme pointers zijn (met expliciete SmartPtr<…> in het resulttype).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor het uitpakken van een object naar nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt om nullable te verpakken.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor het uitpakken van een nullable object.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor enum-verpakking.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor het kopiëren van waardetypen naar de heap wanneer de waardetype als slimme pointer moet worden gerefereerd (in generics beperkt door een interface-type maar gespecificeerd met een structuur die deze interface implementeert).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt om interfaces uit waardetypen te verkrijgen.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor algemene verpakking.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor [System::String](../string/) verpakking.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor het uitpakken van interfaces.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor algemene uitpakking.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor nullptr-casting.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## System::ExplicitCast(const Source\&) functie

Zet het brontype om naar het resulttype met een expliciete cast. Wordt gebruikt voor casting tussen arrays.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

Het cast-resultaat.

## Zie ook

* Typedef [Exception](../exception/)
* Klasse [SmartPtr](../smartptr/)
* Klasse [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)