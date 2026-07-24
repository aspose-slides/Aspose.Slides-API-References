---
title: Insert()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Zeichenkette an die feste Position des Builders ein.
type: docs
weight: 183
url: /de/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) Methode

Fügt eine Zeichenkette an die feste Position des Builders ein.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Position, an der Zeichen eingefügt werden sollen. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Einfügen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Insert(int32_t, const String\&, int32_t) Methode

Fügt wiederholte Zeichenkette an die feste Position des Builders ein.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Position, an der Zeichen eingefügt werden sollen. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) zum Einfügen. |
| count | **int32_t** | Wie oft die Zeichenkette **value** wiederholt werden soll. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Insert(int, char_t) Methode

Fügt ein Zeichen an die feste Position des Builders ein.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Position, an der Zeichen eingefügt werden sollen. |
| ch | char_t | Einzufügenendes Zeichen. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) Methode

Fügt Zeichen in die feste Position des Builders ein.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position, an der Zeichen eingefügt werden sollen. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) zum Einfügen des Slice von. |
| startIndex | int | [Array](../../../system/array/) Slice-Anfangsindex. |
| charCount | int | [Array](../../../system/array/) Slice-Länge. |

### Rückgabewert

Dieser Zeiger.

## StringBuilder::Insert(int, T) Methode

Fügt einen Wert an die feste Position des Builders ein.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Parameter | Typ. |

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Position, an der Zeichen eingefügt werden sollen. |
| value | T | Wert, der formatiert und eingefügt wird. |

### Rückgabewert

Dieser Zeiger.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StringBuilder](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)