---
title: CanCast()
second_title: Aspose.Slides dla C++ - Referencja API
description: Sprawdza możliwość rzutowania.
type: docs
weight: 40
url: /pl/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

True, gdy po rzutowaniu zwracana jest nie nullptr wartość, w przeciwnym razie false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

True, gdy po rzutowaniu zwracana jest nie nullptr wartość, w przeciwnym razie false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

True, gdy po rzutowaniu zwracana jest nie nullptr wartość, w przeciwnym razie false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

Zawsze zwraca true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

True, gdy po rzutowaniu zwracana jest nie nullptr wartość, w przeciwnym razie false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

Zawsze zwraca true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

True, jeśli operacja rzutowania zakończyła się pomyślnie, w przeciwnym razie false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funkcja

Sprawdza możliwość rzutowania.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Source | Typ źródłowy. |
| Result | Typ wynikowy. |

### Wartość zwracana

Zawsze zwraca false.

## See Also

* Struktura [CastType](../casttype/)
* Przestrzeń nazw [System::Collections::Generic::Details::CastRules](../)
* Biblioteka [Aspose.Slides](../../)