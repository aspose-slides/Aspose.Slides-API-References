---
title: Cast()
second_title: Aspose.Slides for C++ API hivatkozás
description: Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a forrás- és a cél típusok megegyeznek.
type: docs
weight: 14
url: /hu/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a forrás- és a cél típusok megegyeznek.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a forrás típust statikusan átalakítható a cél típusra.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a típusok nem egyeznek, és a forrás típust nem lehet statikusan átalakítani a cél típusra.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a forrás típust a [Nullable](../../system/nullable/) osztálypéldányba dobják.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a forrás típust a [Nullable](../../system/nullable/) osztálypéldányból kicsomagolják.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a forrás típust a [Object](../../system/object/) osztálypéldányba dobják.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor a forrás típust a [Object](../../system/object/) osztálypéldányból kicsomagolják.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## System::Collections::Generic::Details::CastRules::Cast(Source) függvény


Átalakítja a forrás típust a cél típusra. Akkor használható, amikor az átalakítás érvénytelen vagy a konverzió explicit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Source | A forrás típus. |
| Result | A cél típus. |

### Visszatérési érték

A cast eredménye.

## Lásd még

* Struktúra [CastType](../casttype/)
* Névterület [System::Collections::Generic::Details::CastRules](../)
* Könyvtár [Aspose.Slides](../../)