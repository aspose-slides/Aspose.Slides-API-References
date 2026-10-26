---
title: DynamicCast()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt ein dynamisches Casting bei Exception-Objekten durch.
type: docs
weight: 2536
url: /de/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) Funktion

Führt dynamisches Casting bei Exception-Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Rückgabewert

Cast result if cast is allowed.

Veraltet
:   Zur Wahrung der Rückwärtskompatibilität beibehalten. Verwenden Sie stattdessen ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) Funktion

Führt dynamisches Casting bei [SmartPtr](../smartptr/)-Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Rückgabewert

Cast result if cast is allowed.

Veraltet
:   Zur Wahrung der Rückwärtskompatibilität beibehalten. Verwenden Sie stattdessen ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\>) Funktion

Entpackt ein verpacktes Enum mittels Cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target enum type. |
| TFrom | Source pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointer to the object to unbox data from. |

### Rückgabewert

Unboxed enum value.

Veraltet
:   Zur Wahrung der Rückwärtskompatibilität beibehalten. Verwenden Sie stattdessen ExplicitCast.

## System::DynamicCast(std::nullptr_t) Funktion

Führt dynamisches Casting von Null-Objekten durch.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target pointee type. |

### Rückgabewert

nullptr.

Veraltet
:   Zur Wahrung der Rückwärtskompatibilität beibehalten. Verwenden Sie stattdessen ExplicitCast.

## System::DynamicCast(TFrom\&) Funktion

Führt dynamisches Casting bei Nicht-Zeiger-Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | TFrom\& | Source object. |

### Rückgabewert

Cast result.

Veraltet
:   Zur Wahrung der Rückwärtskompatibilität beibehalten. Verwenden Sie stattdessen ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\>) Funktion

Führt dynamisches Casting von Objekten zu Exception-Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Rückgabewert

Cast result if cast is allowed.

Veraltet
:   Zur Wahrung der Rückwärtskompatibilität beibehalten. Verwenden Sie stattdessen ExplicitCast.

## System::DynamicCast(TFrom) Funktion

Führt dynamisches Casting von IntPtr zu Zeiger durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | TFrom | Source IntPtr value. |

### Rückgabewert

Cast result.

Veraltet
:   Zur Wahrung der Rückwärtskompatibilität beibehalten. Verwenden Sie stattdessen ExplicitCast.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Klasse [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)