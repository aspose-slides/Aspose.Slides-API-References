---
title: StaticCast_noexcept()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert een statische cast uit op SmartPtr-objecten.
type: docs
weight: 2549
url: /nl/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) functie


Voert een statische cast uit op [SmartPtr](../smartptr/) objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| TTo | Doel-pointee-type. |
| TFrom | Bron-pointee-type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Bronpointer. |

### Retourwaarde

Cast result if cast is allowed or nullptr otherwise.

Verouderd
:   Gelaten voor achterwaartse compatibiliteit. Gebruik AsCast in plaats daarvan.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) functie


Voert een statische cast uit op [WeakPtr](../weakptr/) objecten.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| TTo | Doel-pointee-type. |
| TFrom | Bron-pointee-type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Bronpointer. |

### Retourwaarde

Cast result if cast is allowed or nullptr otherwise.

Verouderd
:   Gelaten voor achterwaartse compatibiliteit. Gebruik AsCast in plaats daarvan.

## System::StaticCast_noexcept(const TFrom\&) functie


Voert een statische cast uit op Exception-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| TTo | Doel Exception-type. |
| TFrom | Bron Exception-type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Bronpointer. |

### Retourwaarde

Cast result if cast is allowed or nullptr otherwise.

Verouderd
:   Gelaten voor achterwaartse compatibiliteit. Gebruik AsCast in plaats daarvan.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) functie


Voert een statische cast uit op Objecten naar Exception-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| TTo | Doel Exception-type. |
| TFrom | [Object](../object/) type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Bronpointer. |

### Retourwaarde

Cast result if cast is allowed or nullptr otherwise.

Verouderd
:   Gelaten voor achterwaartse compatibiliteit. Gebruik AsCast in plaats daarvan.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Klasse [WeakPtr](../weakptr/)
* Klasse [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [CastResult](../castresult/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)