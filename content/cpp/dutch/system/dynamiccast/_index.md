---
title: DynamicCast()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert dynamische casting uit op Exception-objecten.
type: docs
weight: 2536
url: /nl/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) function


Voert dynamische casting uit op Exception-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-Exception-type. |
| TFrom | Bron-Exception-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const TFrom\& | Bron-pointer. |

### Retourwaarde

Castresultaat indien cast is toegestaan.

Verouderd
:   Behoudt voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) function


Voert dynamische casting uit op [SmartPtr](../smartptr/)-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-pointee-type. |
| TFrom | Bron-pointee-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Bron-pointer. |

### Retourwaarde

Castresultaat indien cast is toegestaan.

Verouderd
:   Behoudt voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::DynamicCast(SmartPtr\<TFrom\>) function


Deboxet een verpakte enum via cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-enumtype. |
| TFrom | Bron-pointee-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointer naar het object waaruit gegevens worden gedeboxet. |

### Retourwaarde

Gedeboxte enumwaarde.

Verouderd
:   Behoudt voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::DynamicCast(std::nullptr_t) function


Voert dynamische casting uit op null-objecten.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-pointee-type. |

### Retourwaarde

nullptr.

Verouderd
:   Behoudt voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::DynamicCast(TFrom\&) function


Voert dynamische casting uit op niet-pointerobjecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doeltype. |
| TFrom | Brontype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | TFrom\& | Bronobject. |

### Retourwaarde

Castresultaat.

Verouderd
:   Behoudt voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::DynamicCast(SmartPtr\<TFrom\>) function


Voert dynamische casting uit op Objecten naar Exception-objecten.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doel-Exception-type. |
| TFrom | [Object](../object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Bron-pointer. |

### Retourwaarde

Castresultaat indien cast is toegestaan.

Verouderd
:   Behoudt voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::DynamicCast(TFrom) function


Voert dynamische casting uit van IntPtr naar pointer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TTo | Doeltype. |
| TFrom | Brontype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | TFrom | Bron-IntPtr-waarde. |

### Retourwaarde

Castresultaat.

Verouderd
:   Behoudt voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Klasse [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [CastResult](../castresult/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)