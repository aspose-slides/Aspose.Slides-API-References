---
title: CanCast()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar möjligheten att kasta.
type: docs
weight: 40
url: /sv/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Sant när ett icke-nullptr-värde returneras efter kast, annars falskt.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Sant när ett icke-nullptr-värde returneras efter kast, annars falskt.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Sant när ett icke-nullptr-värde returneras efter kast, annars falskt.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Returnerar alltid sant.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Sant när ett icke-nullptr-värde returneras efter kast, annars falskt.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Returnerar alltid sant.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Sant om kastoperationen utfördes framgångsrikt, annars falskt.

## System::Collections::Generic::Details::CastRules::CanCast(Source) funktion

Kontrollerar möjligheten att kasta.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Source | Källtypen. |
| Result | Resultattypen. |

### Returvärde

Returnerar alltid falskt.

## Se även

* Struktur [CastType](../casttype/)
* Namnrymd [System::Collections::Generic::Details::CastRules](../)
* Bibliotek [Aspose.Slides](../../)