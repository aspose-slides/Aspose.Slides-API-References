---
title: StaticCast_noexcept()
second_title: Aspose.Slides för C++ API-referens
description: Utför statisk typomvandling på SmartPtr-objekt.
type: docs
weight: 2549
url: /sv/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) funktion


Utför statisk typomvandling på [SmartPtr](../smartptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Behålls för bakåtkompatibilitet. Använd AsCast istället.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) funktion


Utför statisk typomvandling på [WeakPtr](../weakptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Behålls för bakåtkompatibilitet. Använd AsCast istället.

## System::StaticCast_noexcept(const TFrom\&) funktion


Utför statisk typomvandling på Exception-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Källpekare. |

### Returvärde

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Behålls för bakåtkompatibilitet. Använd AsCast istället.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) funktion


Utför statisk typomvandling på Objects till Exception-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) typ. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Källpekare. |

### Returvärde

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Behålls för bakåtkompatibilitet. Använd AsCast istället.

## Se även

* Klass [SmartPtr](../smartptr/)
* Klass [WeakPtr](../weakptr/)
* Klass [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)