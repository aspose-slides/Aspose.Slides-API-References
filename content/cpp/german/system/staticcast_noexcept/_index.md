---
title: StaticCast_noexcept()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt einen statischen Cast auf SmartPtr-Objekten aus.
type: docs
weight: 2549
url: /de/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) Funktion


Führt einen statischen Cast auf [SmartPtr](../smartptr/) Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Pointee-Typ. |
| TFrom | Quell-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Quellzeiger. |

### Rückgabewert

Cast-Ergebnis, wenn das Casten zulässig ist, sonst nullptr.

Veraltet
:   Zurückwärtskompatibilität beibehalten. Verwenden Sie stattdessen AsCast.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) Funktion


Führt einen statischen Cast auf [WeakPtr](../weakptr/) Objekten durch.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Pointee-Typ. |
| TFrom | Quell-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Quellzeiger. |

### Rückgabewert

Cast-Ergebnis, wenn das Casten zulässig ist, sonst nullptr.

Veraltet
:   Zurückwärtskompatibilität beibehalten. Verwenden Sie stattdessen AsCast.

## System::StaticCast_noexcept(const TFrom\&) Funktion


Führt einen statischen Cast auf Exception Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Exception-Typ. |
| TFrom | Quell-Exception-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const TFrom\& | Quellzeiger. |

### Rückgabewert

Cast-Ergebnis, wenn das Casten zulässig ist, sonst nullptr.

Veraltet
:   Zurückwärtskompatibilität beibehalten. Verwenden Sie stattdessen AsCast.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) Funktion


Führt einen statischen Cast auf Objekten zu Exception Objekten durch.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Exception-Typ. |
| TFrom | [Object](../object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Quellzeiger. |

### Rückgabewert

Cast-Ergebnis, wenn das Casten zulässig ist, sonst nullptr.

Veraltet
:   Zurückwärtskompatibilität beibehalten. Verwenden Sie stattdessen AsCast.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Klasse [WeakPtr](../weakptr/)
* Klasse [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)