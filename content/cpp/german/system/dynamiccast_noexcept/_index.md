---
title: DynamicCast_noexcept()
second_title: Aspose.Slides für C++ API-Referenz
description: Alte veraltete Casts. Werden in zukünftigen Versionen entfernt.
type: docs
weight: 2523
url: /de/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) Funktion

Alte veraltete Casts. Werden in zukünftigen Versionen entfernt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const TFrom\& | Quellzeiger. |

### Rückgabewert

Castergebnis, wenn der Cast erlaubt ist, andernfalls nullptr.

## Anmerkungen

Führt einen dynamischen Cast auf Exception-Objekten aus. Veraltet
:   Zurückwärtskompatibilität erhalten. Verwenden Sie stattdessen AsCast.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) Funktion

Führt einen dynamischen Cast auf [SmartPtr](../smartptr/)-Objekten aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Quellzeiger. |

### Rückgabewert

Castergebnis, wenn der Cast erlaubt ist, andernfalls nullptr.

Veraltet
:   Zurückwärtskompatibilität erhalten. Verwenden Sie stattdessen AsCast.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) Funktion

Führt einen dynamischen Cast von Objekten zu Exception-Objekten aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Quellzeiger. |

### Rückgabewert

Castergebnis, wenn der Cast erlaubt ist, andernfalls nullptr.

Veraltet
:   Zurückwärtskompatibilität erhalten. Verwenden Sie stattdessen AsCast.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Klasse [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)