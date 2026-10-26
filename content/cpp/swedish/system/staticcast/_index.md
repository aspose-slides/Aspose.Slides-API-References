---
title: StaticCast()
second_title: Aspose.Slides för C++ API-referens
description: Utför statisk kast på SmartPtr-objekt.
type: docs
weight: 2562
url: /sv/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) funktion


Utför statisk kast på [SmartPtr](../smartptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointerns typ. |
| TFrom | Källpointerns typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Behålls för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::StaticCast(WeakPtr\<TFrom\> const\&) funktion


Utför statisk kast på [WeakPtr](../weakptr/)-objekt.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointerns typ. |
| TFrom | Källpointerns typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Behålls för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::StaticCast(std::nullptr_t) funktion


Utför statisk kast av null-objekt.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpointerns typ. |

### Returvärde

nullptr.

Föråldrad
:   Behålls för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::StaticCast(TFrom) funktion


Specialisering för aritmetiska typer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) funktion


Utför kast från [String](../string/) till [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) funktion


Specialisering för aritmetiska typer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) funktion


Utför statisk kast på icke-pekarobjekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Måltyp. |
| TFrom | Källtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const TFrom\& | Källobjekt. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Behålls för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::StaticCast(const TFrom\&) funktion


Utför statisk kast på Exception-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Mål-Exception-typ. |
| TFrom | Käll-Exception-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const TFrom\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Behålls för bakåtkompatibilitet. Använd ExplicitCast istället.

## System::StaticCast(SmartPtr\<TFrom\>) funktion


Utför statisk kast på Objects till Exception-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Mål-Exception-typ. |
| TFrom | [Object](../object/)-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet.

Föråldrad
:   Behålls för bakåtkompatibilitet. Använd ExplicitCast istället.

## Se även

* Klass [SmartPtr](../smartptr/)
* Klass [WeakPtr](../weakptr/)
* Klass [String](../string/)
* Klass [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Struktur [CastResult](../castresult/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)