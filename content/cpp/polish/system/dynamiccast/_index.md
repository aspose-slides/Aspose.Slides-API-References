---
title: DynamicCast()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Wykonuje dynamiczne rzutowanie obiektów Exception.
type: docs
weight: 2536
url: /pl/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) funkcja


Wykonuje dynamiczne rzutowanie obiektów Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
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

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Deprecated
:   Pozostawiono ze względu na zgodność wsteczną. Użyj zamiast tego ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) funkcja


Wykonuje dynamiczne rzutowanie obiektów [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
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

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Deprecated
:   Pozostawiono ze względu na zgodność wsteczną. Użyj zamiast tego ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\>) funkcja


Odbija opakowaną wartość wyliczeniową poprzez rzutowanie.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ wyliczeniowy. |
| TFrom | Źródłowy typ wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Wskaźnik do obiektu, z którego należy rozpakować dane. |

### Wartość zwracana

Rozpakowana wartość wyliczeniowa.

Deprecated
:   Pozostawiono ze względu na zgodność wsteczną. Użyj zamiast tego ExplicitCast.

## System::DynamicCast(std::nullptr_t) funkcja


Wykonuje dynamiczne rzutowanie obiektów null.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ wskaźnika. |

### Wartość zwracana

nullptr.

Deprecated
:   Pozostawiono ze względu na zgodność wsteczną. Użyj zamiast tego ExplicitCast.

## System::DynamicCast(TFrom\&) funkcja


Wykonuje dynamiczne rzutowanie obiektów niebędących wskaźnikami.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ. |
| TFrom | Źródłowy typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | TFrom\& | Obiekt źródłowy. |

### Wartość zwracana

Wynik rzutowania.

Deprecated
:   Pozostawiono ze względu na zgodność wsteczną. Użyj zamiast tego ExplicitCast.

## System::DynamicCast(SmartPtr\<TFrom\>) funkcja


Wykonuje dynamiczne rzutowanie obiektów na obiekty Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ Exception. |
| TFrom | Typ [Object](../object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Wskaźnik źródłowy. |

### Wartość zwracana

Wynik rzutowania, jeśli rzutowanie jest dozwolone.

Deprecated
:   Pozostawiono ze względu na zgodność wsteczną. Użyj zamiast tego ExplicitCast.

## System::DynamicCast(TFrom) funkcja


Wykonuje dynamiczne rzutowanie z IntPtr na wskaźnik.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TTo | Docelowy typ. |
| TFrom | Źródłowy typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | TFrom | Źródłowa wartość IntPtr. |

### Wartość zwracana

Wynik rzutowania.

Deprecated
:   Pozostawiono ze względu na zgodność wsteczną. Użyj zamiast tego ExplicitCast.

## Zobacz również

* Klasa [SmartPtr](../smartptr/)
* Klasa [Object](../object/)
* Struktura [IsExceptionWrapper](../isexceptionwrapper/)
* Struktura [CastResult](../castresult/)
* Struktura [IsSmartPtr](../issmartptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)