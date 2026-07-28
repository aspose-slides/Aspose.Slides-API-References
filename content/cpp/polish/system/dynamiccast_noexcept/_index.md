---
title: DynamicCast_noexcept()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Stare przestarzałe rzutowania. Zostaną usunięte w przyszłych wersjach.
type: docs
weight: 2523
url: /pl/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) funkcja


Stare przestarzałe rzutowania. Zostaną usunięte w przyszłych wersjach.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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

Cast result if cast is allowed or nullptr otherwise.

## Uwaga

Wykonuje dynamiczne rzutowanie na obiektach Exception. Przestarzałe
:   Left for backwards compatibility. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) funkcja


Wykonuje dynamiczne rzutowanie na [SmartPtr](../smartptr/) obiektach.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ wskazywanego. |
| TFrom | Źródłowy typ wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Wskaźnik źródłowy. |

### Wartość zwracana

Cast result if cast is allowed or nullptr otherwise.

Przestarzałe
:   Left for backwards compatibility. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) funkcja


Wykonuje dynamiczne rzutowanie obiektów na obiekty Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ Exception. |
| TFrom | [Object](../object/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Wskaźnik źródłowy. |

### Wartość zwracana

Cast result if cast is allowed or nullptr otherwise.

Przestarzałe
:   Left for backwards compatibility. Use AsCast instead.

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Klasa [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)