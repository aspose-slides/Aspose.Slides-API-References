---
title: DynamicCast_noexcept()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Staré zastaralé konverze. Budou odstraněny v budoucích verzích.
type: docs
weight: 2523
url: /cs/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) funkce


Staré zastaralé konverze. Budou odstraněny v budoucích verzích.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Návratová hodnota

Cast result if cast is allowed or nullptr otherwise.
## Poznámky


Provádí dynamické přetypování na objektech Exception. Zastaralé
:   Ponecháno pro zpětnou kompatibilitu. Použijte AsCast místo toho.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) funkce


Provádí dynamické přetypování na [SmartPtr](../smartptr/) objektech.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Návratová hodnota

Cast result if cast is allowed or nullptr otherwise.

Zastaralé
:   Ponecháno pro zpětnou kompatibilitu. Použijte AsCast místo toho.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) funkce


Provádí dynamické přetypování objektů na objekty Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Návratová hodnota

Cast result if cast is allowed or nullptr otherwise.

Zastaralé
:   Ponecháno pro zpětnou kompatibilitu. Použijte AsCast místo toho.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Třída [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)