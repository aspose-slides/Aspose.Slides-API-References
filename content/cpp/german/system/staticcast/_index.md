---
title: StaticCast()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt einen statischen Cast auf SmartPtr-Objekten aus.
type: docs
weight: 2562
url: /de/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) Funktion

Führt einen statischen Cast auf [SmartPtr](../smartptr/)-Objekten aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
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

Cast-Ergebnis, falls der Cast zulässig ist.

Veraltet
:   Zurückgelassen zur Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## System::StaticCast(WeakPtr\<TFrom\> const\&) Funktion

Führt einen statischen Cast auf [WeakPtr](../weakptr/)-Objekten aus.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
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

Cast-Ergebnis, falls der Cast zulässig ist.

Veraltet
:   Zurückgelassen zur Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## System::StaticCast(std::nullptr_t) Funktion

Führt einen statischen Cast von Null-Objekten aus.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Ziel-Pointee-Typ. |

### Rückgabewert

nullptr.

Veraltet
:   Zurückgelassen zur Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## System::StaticCast(TFrom) Funktion

Spezialisierung für arithmetische Typen.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) Funktion

Verarbeitet den Cast von [String](../string/) nach [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) Funktion

Spezialisierung für arithmetische Typen.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) Funktion

Führt einen statischen Cast auf Nicht-Zeiger-Objekten aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TTo | Zieltyp. |
| TFrom | Quelltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const TFrom\& | Quellobjekt. |

### Rückgabewert

Cast-Ergebnis, falls der Cast zulässig ist.

Veraltet
:   Zurückgelassen zur Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## System::StaticCast(const TFrom\&) Funktion

Führt einen statischen Cast auf Exception-Objekten aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
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

Cast-Ergebnis, falls der Cast zulässig ist.

Veraltet
:   Zurückgelassen zur Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## System::StaticCast(SmartPtr\<TFrom\>) Funktion

Führt einen statischen Cast von Objekten zu Exception-Objekten aus.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
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

Cast-Ergebnis, falls der Cast zulässig ist.

Veraltet
:   Zurückgelassen zur Abwärtskompatibilität. Verwenden Sie stattdessen ExplicitCast.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Klasse [WeakPtr](../weakptr/)
* Klasse [String](../string/)
* Klasse [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)