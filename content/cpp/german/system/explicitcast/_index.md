---
title: ExplicitCast()
second_title: Aspose.Slides für C++ API-Referenz
description: Wandelt den Quelltyp mithilfe eines expliziten Casts in den Ergebnistyp um. Wird verwendet, wenn Quell- und Ergebnistyp identisch sind.
type: docs
weight: 2627
url: /de/system/explicitcast/
---
## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird verwendet, wenn Quell- und Ergebnis-Typ identisch sind.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird verwendet, wenn ein einfacher konstruktorähnlicher Cast benötigt wird.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird für Ausnahme-Wrapper verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird zum Casten eines Objekts in eine Ausnahme verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird verwendet, wenn Quell- und Ergebnis-Typ beide Smart-Pointer sind (ohne explizites SmartPtr<…> im Ergebnis-Typ).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(Source) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird verwendet, wenn ein roher Zeiger in einen Smart-Pointer gecastet wird.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | Source | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird verwendet, wenn Quell- und Ergebnis-Typ beide Smart-Pointer sind (mit explizitem SmartPtr<…> im Ergebnis-Typ).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird zum Entpacken (Unboxing) eines Objekts in ein Nullable verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird zum Verpacken (Boxing) eines Nullable verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird zum Entpacken (Unboxing) eines Nullable-Objekts verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird zum Boxen eines Aufzählungswertes (Enum) verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird verwendet, um Werttypen in den Heap zu kopieren, wenn der Werttyp als Smart-Pointer referenziert werden soll (in Generics, die mit einem Interface-Typ eingeschränkt, aber mit einer Struktur, die dieses Interface implementiert, spezialisiert werden).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird verwendet, um Schnittstellen aus Werttypen zu erhalten.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird für allgemeines Boxing verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird für [System::String](../string/)-Boxing verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird zum Entpacken von Schnittstellen verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird für allgemeines Unboxing verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnistyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird für das Casten von nullptr verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnis-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::ExplicitCast(const Source\&) Funktion

Wandelt den Quelltyp in den Ergebnistyp mittels explizitem Cast um. Wird zum Casten zwischen Arrays verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Ergebnis-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## Siehe auch

* Typedef [Exception](../exception/)
* Klasse [SmartPtr](../smartptr/)
* Klasse [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namensraum [System](../)
* Library [Aspose.Slides](../../)