---
title: AsCast()
second_title: Aspose.Slides für C++ API-Referenz
description: Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird verwendet, wenn ein einfacher, konstruktorähnlicher Cast benötigt wird.
type: docs
weight: 2640
url: /de/system/ascast/
---
## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird verwendet, wenn ein einfacher, konstruktorähnlicher Cast benötigt wird.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird verwendet, wenn Quell- und Zieltyp identisch sind.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird für Ausnahme-Wrapper verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird zum Casten eines Objekts in eine Ausnahme verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird verwendet, wenn sowohl Quelle als auch Ziel Smart-Pointer sind.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird verwendet, wenn sowohl Quelle als auch Ziel Smart-Pointer sind (mit explizitem SmartPtr<...> im Zieltyp).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis. Gibt nullptr zurück, wenn keine Konvertierung verfügbar ist.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird zum Unboxing eines Objekts in ein Nullable verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis. Gibt ein leeres Nullable zurück, wenn keine Konvertierung verfügbar ist.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Ungültiges Unboxing zu einem Nicht-Objekt-Typ.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Gibt immer null zurück.

## System::AsCast(const Source\&) Funktion


Ungültiges Unboxing zu einem Nicht-Objekt-Typ.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Gibt immer null zurück.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird zum Boxen eines Nullable-Objekts verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird zum Boxen eines allgemeinen Objekts verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird zum Boxen eines allgemeinen Objekts verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird für das Unboxing von Zeichenketten verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird für das Casten von nullptr verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis.

## System::AsCast(const Source\&) Funktion


Wandelt den Quelltyp mit dem 'as'-Operator in den Zieltyp um. Wird zum Casten zwischen Arrays verwendet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Source | Der Quelltyp. |
| Result | Der Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) zum Casten. |

### Rückgabewert

Das Cast-Ergebnis. Gibt nullptr zurück, wenn für kein Array-Element eine Konvertierung verfügbar ist.

## Siehe auch

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)