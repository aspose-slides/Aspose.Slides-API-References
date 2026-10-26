---
title: DynamicCast()
second_title: Aspose.Slides för C++ API-referens
description: Utför dynamisk kastning på Exception-objekt.
type: docs
weight: 2536
url: /sv/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) funktion


Utför dynamisk kastning på Exception-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målexceptionstyp. |
| TFrom | Käll-Exception-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const TFrom\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) funktion


Utför dynamisk kastning på [SmartPtr](../smartptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |
| TFrom | Källpointee-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::DynamicCast(SmartPtr\<TFrom\>) funktion


Packar upp en inkapslad enum via kast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målenumtyp. |
| TFrom | Källpointee-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pekare till objektet att packa upp data från. |

### Returvärde

Uppackat enumvärde.

Föråldrad
:   Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::DynamicCast(std::nullptr_t) funktion


Utför dynamisk kastning av null-objekt.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointee-typ. |

### Returvärde

nullptr.

Föråldrad
:   Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::DynamicCast(TFrom\&) funktion


Utför dynamisk kastning på icke-pekarobjekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Måtyp. |
| TFrom | Källtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | TFrom\& | Källobjekt. |

### Returvärde

Kastresultat.

Föråldrad
:   Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::DynamicCast(SmartPtr\<TFrom\>) funktion


Utför dynamisk kastning på Objects till Exception-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målexceptionstyp. |
| TFrom | [Object](../object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::DynamicCast(TFrom) funktion


Utför dynamisk kastning från IntPtr till pekare.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Måtyp. |
| TFrom | Källtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | TFrom | Käll IntPtr-värde. |

### Returvärde

Kastresultat.

Föråldrad
:   Lämnad för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Klass [SmartPtr](../smartptr/)
* Klass [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namnområde [System](../)
* Bibliotek [Aspose.Slides](../../)