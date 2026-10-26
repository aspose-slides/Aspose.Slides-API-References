---
title: LastIndexOfAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Durchsucht die gesamte Zeichenkette rückwärts nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen der Zeichenkette mit allen Zeichen in anyOf, dann das vorherige und so weiter. Gibt den Index des ersten gefundenen Treffers zurück.
type: docs
weight: 664
url: /de/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const Methode

Durchsucht die gesamte Zeichenkette rückwärts nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen der Zeichenkette mit allen Zeichen in anyOf, dann das vorherige und so weiter. Gibt den Index des ersten gefundenen Treffers zurück.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist unwichtig. |

### Rückgabewert

[Index](../../index/) des letzten passenden Zeichens oder -1, wenn nicht gefunden.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const Methode

Durchsucht das Teilzeichenketten-Substring rückwärts nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen der Zeichenkette mit allen Zeichen in anyOf, dann das vorherige und so weiter. Gibt den Index des ersten gefundenen Treffers zurück.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist unwichtig. |
| startindex | **int32_t** | [Index](../../index/) um die Suche zu starten. |

### Rückgabewert

[Index](../../index/) des letzten passenden Zeichens oder -1, wenn nicht gefunden.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const Methode

Durchsucht das Teilzeichenketten-Substring rückwärts nach einem der übergebenen Zeichen. Vergleicht das letzte Zeichen der Zeichenkette mit allen Zeichen in anyOf, dann das vorherige und so weiter. Gibt den Index des ersten gefundenen Treffers zurück.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) von Zeichen, nach denen gesucht werden soll. Die Reihenfolge ist unwichtig. |
| startindex | **int32_t** | [Index](../../index/) um die Suche zu starten. |
| count | **int32_t** | Anzahl der Zeichen, die durchsucht werden sollen. |

### Rückgabewert

[Index](../../index/) des letzten passenden Zeichens oder -1, wenn nicht gefunden.

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)