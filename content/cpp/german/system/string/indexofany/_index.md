---
title: IndexOfAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Vorwärtssuche nach Zeichen.
type: docs
weight: 638
url: /de/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const Methode

Vorwärtssuche nach Zeichen.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | char_t | Zeichen, nach dem gesucht wird. |
| startIndex | int | [Index](../../index/) zum Starten der Suche bei. |

### Rückgabewert

[Index](../../index/) der ersten Zeichenposition seit startIndex oder -1, wenn nicht gefunden.

## String::IndexOfAny(const String\&, int) const Methode

Durchsucht daher alle Zeichen von str in diesem. Wird das erste Zeichen gefunden, wird seine Position zurückgegeben, andernfalls wird das zweite Zeichen usw. gesucht.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) der zu suchenden Zeichen. Die Reihenfolge der Zeichen ist wichtig. |
| startIndex | int | Position, ab der die Suche gestartet wird. |

### Rückgabewert

[Index](../../index/) des zuerst gefundenen Zeichens oder -1, wenn keines gefunden wurde.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const Methode

Sucht nach beliebigen der übergebenen Zeichen im gesamten String. Vergleicht das erste Zeichen des Strings mit allen Zeichen in anyOf, dann das zweite usw. Gibt den Index des ersten Zeichens zurück, das mit einem der Zielzeichen übereinstimmt.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) der zu suchenden Zeichen. Die Reihenfolge spielt keine Rolle. |

### Rückgabewert

[Index](../../index/) des ersten passenden Zeichens oder -1, wenn nicht gefunden.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const Methode

Sucht nach beliebigen der übergebenen Zeichen im Teilstring. Vergleicht das erste Zeichen des Strings mit allen Zeichen in anyOf, dann das zweite usw. Gibt den Index des ersten Zeichens zurück, das mit einem der Zielzeichen übereinstimmt.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) der zu suchenden Zeichen. Die Reihenfolge spielt keine Rolle. |
| startindex | **int32_t** | [Index](../../index/) zum Starten der Suche ab. |

### Rückgabewert

[Index](../../index/) des ersten passenden Zeichens oder -1, wenn nicht gefunden.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const Methode

Sucht nach beliebigen der übergebenen Zeichen im Teilstring. Vergleicht das erste Zeichen des Strings mit allen Zeichen in anyOf, dann das zweite usw. Gibt den Index des ersten Zeichens zurück, das mit einem der Zielzeichen übereinstimmt.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) der zu suchenden Zeichen. Die Reihenfolge spielt keine Rolle. |
| startindex | **int32_t** | [Index](../../index/) zum Starten der Suche ab. |
| count | **int32_t** | Anzahl der zu durchsuchenden Zeichen. |

### Rückgabewert

[Index](../../index/) des ersten passenden Zeichens oder -1, wenn nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)