---
title: StaticCast_noexcept()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wykonuje statyczne rzutowanie na obiekty SmartPtr.
type: docs
weight: 2549
url: /pl/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) funkcja


Wykonuje statyczne rzutowanie na [SmartPtr](../smartptr/) obiekty.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ wskaźnika. |
| TFrom | Źródłowy typ wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone, lub nullptr w przeciwnym razie.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj AsCast zamiast tego.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) funkcja


Wykonuje statyczne rzutowanie na [WeakPtr](../weakptr/) obiekty.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ wskaźnika. |
| TFrom | Źródłowy typ wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone, lub nullptr w przeciwnym razie.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj AsCast zamiast tego.

## System::StaticCast_noexcept(const TFrom\&) funkcja


Wykonuje statyczne rzutowanie na obiekty Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ Exception. |
| TFrom | Źródłowy typ Exception. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const TFrom\& | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone, lub nullptr w przeciwnym razie.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj AsCast zamiast tego.

## System::StaticCast_nothrow(SmartPtr\<TFrom\>) funkcja


Wykonuje statyczne rzutowanie obiektów na obiekty Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ Exception. |
| TFrom | typ [Object](../object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone, lub nullptr w przeciwnym razie.

Przestarzałe
:   Pozostawiono ze względu na kompatybilność wsteczną. Użyj AsCast zamiast tego.

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Klasa [WeakPtr](../weakptr/)
* Klasa [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Struktura [CastResult](../castresult/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)