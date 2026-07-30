---
title: DynamicCast()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Provádí dynamické přetypování objektů výjimky.
type: docs
weight: 2536
url: /cs/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) funkce


Provádí dynamické přetypování objektů výjimky.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ výjimky. |
| TFrom | Zdrojový typ výjimky. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const TFrom\& | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) funkce


Provádí dynamické přetypování objektů [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\>) funkce


Rozbalí zabalený výčtový typ pomocí přetypování.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ výčtu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Ukazatel na objekt, ze kterého se mají rozbalit data. |

### Návratová hodnota

Rozbalená hodnota výčtu.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## System::DynamicCast(std::nullptr_t) funkce


Provádí dynamické přetypování nulových objektů.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |

### Návratová hodnota

nullptr.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## System::DynamicCast(TFrom\&) funkce


Provádí dynamické přetypování neukazatelových objektů.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ. |
| TFrom | Zdrojový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | TFrom\& | Zdrojový objekt. |

### Návratová hodnota

Výsledek přetypování.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\>) funkce


Provádí dynamické přetypování objektů na objekty výjimky.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ výjimky. |
| TFrom | [Object](../object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek přetypování, pokud je přetypování povoleno.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## System::DynamicCast(TFrom) funkce


Provádí dynamické přetypování z IntPtr na ukazatel.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TTo | Cílový typ. |
| TFrom | Zdrojový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | TFrom | Zdrojová hodnota IntPtr. |

### Návratová hodnota

Výsledek přetypování.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte místo toho ExplicitCast.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Třída [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Struktura [CastResult](../castresult/)
* Struktura [IsSmartPtr](../issmartptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)