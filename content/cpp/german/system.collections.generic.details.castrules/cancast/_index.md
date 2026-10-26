---
title: CanCast()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft die Cast-Möglichkeit.
type: docs
weight: 40
url: /de/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Wahr, wenn ein Wert ungleich nullptr nach dem Casten zurückgegeben wird, andernfalls falsch.

## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Wahr, wenn ein Wert ungleich nullptr nach dem Casten zurückgegeben wird, andernfalls falsch.

## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Wahr, wenn ein Wert ungleich nullptr nach dem Casten zurückgegeben wird, andernfalls falsch.

## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Gibt immer wahr zurück.

## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Wahr, wenn ein Wert ungleich nullptr nach dem Casten zurückgegeben wird, andernfalls falsch.

## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Gibt immer wahr zurück.

## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Wahr, wenn die Cast-Operation erfolgreich durchgeführt wurde, andernfalls falsch.

## System::Collections::Generic::Details::CastRules::CanCast(Source) Funktion

Überprüft die Cast-Möglichkeit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Rückgabewert

Gibt immer falsch zurück.

## Siehe auch

* Struktur [CastType](../casttype/)
* Namensraum [System::Collections::Generic::Details::CastRules](../)
* Bibliothek [Aspose.Slides](../../)