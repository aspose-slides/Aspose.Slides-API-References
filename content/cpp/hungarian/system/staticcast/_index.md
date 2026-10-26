---
title: StaticCast()
second_title: Aspose.Slides C++ API referencia
description: Statikus átalakítást hajt végre SmartPtr objektumokon.
type: docs
weight: 2562
url: /hu/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) függvény


Statikus átalakítást hajt végre a [SmartPtr](../smartptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| TTo | Cél mutatott típus. |
| TFrom | Forrás mutatott típus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Forrásmutató. |

### Visszatérési érték

Átalakítás eredménye, ha az átalakítás engedélyezett.

Elavult
:   A visszafelé kompatibilitás érdekében hagyják meg. Használja helyette az ExplicitCast-et.

## System::StaticCast(WeakPtr\<TFrom\> const\&) függvény


Statikus átalakítást hajt végre a [WeakPtr](../weakptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| TTo | Cél mutatott típus. |
| TFrom | Forrás mutatott típus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Forrásmutató. |

### Visszatérési érték

Átalakítás eredménye, ha az átalakítás engedélyezett.

Elavult
:   A visszafelé kompatibilitás érdekében hagyják meg. Használja helyette az ExplicitCast-et.

## System::StaticCast(std::nullptr_t) függvény


Statikus átalakítást hajt végre null objektumok esetén.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| TTo | Cél mutatott típus. |

### Visszatérési érték

nullptr.

Elavult
:   A visszafelé kompatibilitás érdekében hagyják meg. Használja helyette az ExplicitCast-et.

## System::StaticCast(TFrom) függvény


Specializáció aritmetikus típusokra.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) függvény


Átalakítást végez a [String](../string/) és a [String](../string/) között.

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) függvény


Specializáció aritmetikus típusokra.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) függvény


Statikus átalakítást hajt végre nem mutató objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| TTo | Cél típus. |
| TFrom | Forrás típus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Forrásobjektum. |

### Visszatérési érték

Átalakítás eredménye, ha az átalakítás engedélyezett.

Elavult
:   A visszafelé kompatibilitás érdekében hagyják meg. Használja helyette az ExplicitCast-et.

## System::StaticCast(const TFrom\&) függvény


Statikus átalakítást hajt végre Exception objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| TTo | Cél Exception típus. |
| TFrom | Forrás Exception típus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Forrásmutató. |

### Visszatérési érték

Átalakítás eredménye, ha az átalakítás engedélyezett.

Elavult
:   A visszafelé kompatibilitás érdekében hagyják meg. Használja helyette az ExplicitCast-et.

## System::StaticCast(SmartPtr\<TFrom\>) függvény


Statikus átalakítást hajt végre Objektumokról Exception objektumokra.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| TTo | Cél Exception típus. |
| TFrom | [Object](../object/) típus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Forrásmutató. |

### Visszatérési érték

Átalakítás eredménye, ha az átalakítás engedélyezett.

Elavult
:   A visszafelé kompatibilitás érdekében hagyják meg. Használja helyette az ExplicitCast-et.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Osztály [WeakPtr](../weakptr/)
* Osztály [String](../string/)
* Osztály [Object](../object/)
* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Struktúra [CastResult](../castresult/)
* Struktúra [IsSmartPtr](../issmartptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)