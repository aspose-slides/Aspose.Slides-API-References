---
title: Cast()
second_title: Aspose.Slides für C++ API-Referenz
description: Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn Quell- und Ergebnistyp identisch sind.
type: docs
weight: 14
url: /de/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn Quell- und Ergebnistyp identisch sind.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp statisch in den Ergebnistyp umgewandelt werden kann.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn die Typen nicht identisch sind und der Quelltyp nicht statisch in den Ergebnistyp umgewandelt werden kann.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp in die Klasseninstanz [Nullable](../../system/nullable/) verpackt wird.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp aus der Klasseninstanz [Nullable](../../system/nullable/) entpackt wird.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp in die Klasseninstanz [Object](../../system/object/) verpackt wird.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn der Quelltyp aus der Klasseninstanz [Object](../../system/object/) entpackt wird.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) Funktion


Wandelt den Quelltyp in den Ergebnistyp um. Wird verwendet, wenn das Casting ungültig ist oder die Konvertierung explizit erfolgt.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Rückgabewert

The cast result.

## Siehe auch

* Struct [CastType](../casttype/)
* Namensraum [System::Collections::Generic::Details::CastRules](../)
* Bibliothek [Aspose.Slides](../../)