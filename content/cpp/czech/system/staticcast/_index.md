---
title: StaticCast()
second_title: Aspose.Slides pro C++ - reference API
description: Provádí statický převod na objektech SmartPtr.
type: docs
weight: 2562
url: /cs/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) funkce


Provede statický převod na objektech typu [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek převodu, pokud je převod povolen.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## System::StaticCast(WeakPtr\<TFrom\> const\&) funkce


Provede statický převod na objektech typu [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |
| TFrom | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek převodu, pokud je převod povolen.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## System::StaticCast(std::nullptr_t) funkce


Provede statický převod nulových objektů.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ ukazovaného objektu. |

### Návratová hodnota

nullptr.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## System::StaticCast(TFrom) funkce


Specializace pro aritmetické typy.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) funkce


Zpracuje převod z [String](../string/) na [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) funkce


Specializace pro aritmetické typy.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) funkce


Provede statický převod na objektech, které nejsou ukazateli.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ. |
| TFrom | Zdrojový typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Zdrojový objekt. |

### Návratová hodnota

Výsledek převodu, pokud je převod povolen.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## System::StaticCast(const TFrom\&) funkce


Provede statický převod na objektech výjimky.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ výjimky. |
| TFrom | Zdrojový typ výjimky. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek převodu, pokud je převod povolen.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## System::StaticCast(SmartPtr\<TFrom\>) funkce


Provede statický převod objektů na objekty výjimky.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TTo | Cílový typ výjimky. |
| TFrom | [Object](../object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Zdrojový ukazatel. |

### Návratová hodnota

Výsledek převodu, pokud je převod povolen.

Zastaralé
:   Zůstává pro zpětnou kompatibilitu. Použijte ExplicitCast místo toho.

## Viz také

* Třída [SmartPtr](../smartptr/)
* Třída [WeakPtr](../weakptr/)
* Třída [String](../string/)
* Třída [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Struktura [CastResult](../castresult/)
* Struktura [IsSmartPtr](../issmartptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)