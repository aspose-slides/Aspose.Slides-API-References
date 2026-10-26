---
title: StaticCast_noexcept()
second_title: Aspose.Slides pro C++ API Reference
description: Provádí statické přetypování objektů SmartPtr.
type: docs
weight: 2549
url: /cs/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) funkce


Provádí statické přetypování na objektech [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Ukazatel na zdroj. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno, nebo nullptr jinak.

Zastaralé
:   Ponecháno pro zpětnou kompatibilitu. Použijte AsCast místo toho.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) funkce


Provádí statické přetypování na objektech [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Ukazatel na zdroj. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno, nebo nullptr jinak.

Zastaralé
:   Ponecháno pro zpětnou kompatibilitu. Použijte AsCast místo toho.

## System::StaticCast_noexcept(const TFrom\&) funkce


Provádí statické přetypování na objektech výjimek.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ výjimky. |
| TFrom | Zdrojový typ výjimky. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Ukazatel na zdroj. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno, nebo nullptr jinak.

Zastaralé
:   Ponecháno pro zpětnou kompatibilitu. Použijte AsCast místo toho.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) funkce


Provádí statické přetypování objektů na objekty výjimek.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ výjimky. |
| TFrom | [Object](../object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Ukazatel na zdroj. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno, nebo nullptr jinak.

Zastaralé
:   Ponecháno pro zpětnou kompatibilitu. Použijte AsCast místo toho.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Třída [WeakPtr](../weakptr/)
* Třída [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Struktura [CastResult](../castresult/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)