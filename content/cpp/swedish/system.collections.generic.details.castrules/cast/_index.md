---
title: Cast()
second_title: Aspose.Slides för C++ API-referens
description: Kastar källtypen till resultattypen. Används när käll- och resultattyperna är desamma.
type: docs
weight: 14
url: /sv/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när käll- och resultattyperna är desamma.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när källtypen kan statiskt kastas till resultattypen.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när typerna inte är desamma och källtypen inte kan statiskt kastas till resultattypen.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när källtypen blir boxad till [Nullable](../../system/nullable/) klassinstans.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när källtypen blir unboxad från [Nullable](../../system/nullable/) klassinstans.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när källtypen blir boxad till [Object](../../system/object/) klassinstans.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när källtypen blir unboxad från [Object](../../system/object/) klassinstans.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## System::Collections::Generic::Details::CastRules::Cast(Source) funktion


Kastar källtypen till resultattypen. Används när kastet är ogiltigt eller konverteringen är explicit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Returvärde

Kastresultatet.

## Se även

* Struktur [CastType](../casttype/)
* Namnrymd [System::Collections::Generic::Details::CastRules](../)
* Bibliotek [Aspose.Slides](../../)