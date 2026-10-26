---
title: StaticCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een statische cast uit op SmartPtr-objecten.
type: docs
weight: 2562
url: /nl/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) functie


Voert een statische cast uit op [SmartPtr](../smartptr/) objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Retourwaarde

Castresultaat als cast is toegestaan.

Verouderd
:   Behoud voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::StaticCast(WeakPtr\<TFrom\> const\&) functie


Voert een statische cast uit op [WeakPtr](../weakptr/) objecten.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Source pointer. |

### Retourwaarde

Castresultaat als cast is toegestaan.

Verouderd
:   Behoud voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::StaticCast(std::nullptr_t) functie


Voert een statische cast uit van nulobjecten.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Target pointee type. |

### Retourwaarde

nullptr.

Verouderd
:   Behoud voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::StaticCast(TFrom) functie


Specialisatie voor rekenkundige types.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) functie


Voert een cast uit van [String](../string/) naar [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) functie


Specialisatie voor rekenkundige types.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) functie


Voert een statische cast uit op niet-pointerobjecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const TFrom\& | Source object. |

### Retourwaarde

Castresultaat als cast is toegestaan.

Verouderd
:   Behoud voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::StaticCast(const TFrom\&) functie


Voert een statische cast uit op Exception-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Retourwaarde

Castresultaat als cast is toegestaan.

Verouderd
:   Behoud voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::StaticCast(SmartPtr\<TFrom\>) functie


Voert een statische cast uit op Objecten naar Exception-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Bronpointer. |

### Retourwaarde

Castresultaat als cast is toegestaan.

Verouderd
:   Behoud voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Klasse [WeakPtr](../weakptr/)
* Klasse [String](../string/)
* Klasse [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [CastResult](../castresult/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)