---
title: DynamicCast_noexcept()
second_title: Aspose.Slides voor C++ API-referentie
description: Oude verouderde casts. Wordt in toekomstige versies verwijderd.
type: docs
weight: 2523
url: /nl/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) functie


Oude verouderde casts. Wordt in toekomstige versies verwijderd.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel Exception-type. |
| TFrom | Bron Exception-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const TFrom\& | Bronpointer. |

### Retourwaarde

Cast-resultaat als cast is toegestaan of nullptr anderszins.
## Opmerkingen


Voert dynamisch casten uit op Exception-objecten. Verouderd
:   Behouwens voor compatibiliteit met eerdere versies. Gebruik AsCast in plaats daarvan.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) functie


Voert dynamisch casten uit op [SmartPtr](../smartptr/)-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-pointee-type. |
| TFrom | Bron-pointee-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Bronpointer. |

### Retourwaarde

Cast-resultaat als cast is toegestaan of nullptr anderszins.

Verouderd
:   Behouwens voor compatibiliteit met eerdere versies. Gebruik AsCast in plaats daarvan.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) functie


Voert dynamisch casten uit op Objecten naar Exception-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel Exception-type. |
| TFrom | [Object](../object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Bronpointer. |

### Retourwaarde

Cast-resultaat als cast is toegestaan of nullptr anderszins.

Verouderd
:   Behouwens voor compatibiliteit met eerdere versies. Gebruik AsCast in plaats daarvan.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Klasse [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)