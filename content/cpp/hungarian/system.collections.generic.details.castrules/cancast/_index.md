---
title: CanCast()
second_title: Aspose.Slides for C++ API referenciája
description: Ellenőrzi a cast lehetőségét.
type: docs
weight: 40
url: /hu/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Igaz, ha a cast után nem nullptr érték tér vissza, egyébként hamis.

## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Igaz, ha a cast után nem nullptr érték tér vissza, egyébként hamis.

## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Igaz, ha a cast után nem nullptr érték tér vissza, egyébként hamis.

## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Mindig true értéket ad vissza.

## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Igaz, ha a cast után nem nullptr érték tér vissza, egyébként hamis.

## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Mindig true értéket ad vissza.

## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Igaz, ha a cast művelet sikeresen végrehajtásra került, egyébként hamis.

## System::Collections::Generic::Details::CastRules::CanCast(Source) függvény

Ellenőrzi a cast lehetőségét.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrástípus. |
| Result | Az eredmény típus. |

### Visszatérési érték

Mindig false értéket ad vissza.

## Lásd még

* Struktúra [CastType](../casttype/)
* Névtér [System::Collections::Generic::Details::CastRules](../)
* Könyvtár [Aspose.Slides](../../)