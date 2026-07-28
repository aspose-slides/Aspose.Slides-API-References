---
title: StaticCast()
second_title: Aspose.Slides dla C++ – referencja API
description: Wykonuje statyczne rzutowanie obiektów SmartPtr.
type: docs
weight: 2562
url: /pl/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) funkcja


Wykonuje statyczne rzutowanie obiektów [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Typ elementu docelowego. |
| TFrom | Typ elementu źródłowego. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj zamiast tego ExplicitCast.


## System::StaticCast(WeakPtr\<TFrom\> const\&) funkcja


Wykonuje statyczne rzutowanie obiektów [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Typ elementu docelowego. |
| TFrom | Typ elementu źródłowego. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj zamiast tego ExplicitCast.


## System::StaticCast(std::nullptr_t) funkcja


Wykonuje statyczne rzutowanie obiektów null.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Typ elementu docelowego. |

### Wartość zwracana

nullptr.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj zamiast tego ExplicitCast.


## System::StaticCast(TFrom) funkcja


Specjalizacja dla typów arytmetycznych.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) funkcja


Przetwarzaj rzutowanie z [String](../string/) do [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) funkcja


Specjalizacja dla typów arytmetycznych.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) funkcja


Wykonuje statyczne rzutowanie obiektów niebędących wskaźnikami.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Typ docelowy. |
| TFrom | Typ źródłowy. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Obiekt źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj zamiast tego ExplicitCast.


## System::StaticCast(const TFrom\&) funkcja


Wykonuje statyczne rzutowanie obiektów Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Typ Exception docelowego. |
| TFrom | Typ Exception źródłowego. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj zamiast tego ExplicitCast.


## System::StaticCast(SmartPtr\<TFrom\>) funkcja


Wykonuje statyczne rzutowanie obiektów na obiekty Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| TTo | Typ Exception docelowego. |
| TFrom | [Object](../object/) typ. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj zamiast tego ExplicitCast.


## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Klasa [WeakPtr](../weakptr/)
* Klasa [String](../string/)
* Klasa [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Struktura [CastResult](../castresult/)
* Struktura [IsSmartPtr](../issmartptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)