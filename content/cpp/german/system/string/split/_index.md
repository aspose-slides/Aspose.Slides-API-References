---
title: Split()
second_title: Aspose.Slides für C++ API-Referenz
description: Teilt die Zeichenkette anhand eines Zeichens.
type: docs
weight: 768
url: /de/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines Zeichens.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | char_t | Zeichen, nach dem die Zeichenkette geteilt wird. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(char_t, int32_t, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines Zeichens.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | char_t | Zeichen, nach dem die Zeichenkette geteilt wird. |
| count | **int32_t** | Die maximale Anzahl zurückzugebender Teilstrings. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(char_t, char_t, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines von zwei Zeichen.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorA | char_t | Erstes Zeichen, nach dem die Zeichenkette geteilt wird. |
| separatorB | char_t | Zweites Zeichen, nach dem die Zeichenkette geteilt wird. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines der angegebenen Zeichen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) von Trennzeichen-Zeichen. Falls leer, wird jedes Leerzeichenzeichen als Trennzeichen betrachtet. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines der angegebenen Zeichen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) von Trennzeichen-Zeichen. Falls leer, wird jedes Leerzeichenzeichen als Trennzeichen betrachtet. |
| count | **int32_t** | Die maximale Anzahl zurückzugebender Teilstrings. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(const String\&, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines Teilstrings.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const [String](../)\& | Teilstring, der als Trennzeichen dient. Falls leer, wirkt ein Leerzeichen als Trennzeichen. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(const String\&, int, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines Teilstrings.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separator | const [String](../)\& | Teilstring, der als Trennzeichen dient. Falls leer, wirkt ein Leerzeichen als Trennzeichen. |
| count | int | Maximale Anzahl von Elementen im Ergebnis-Array. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines Teilstrings.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) von Trennzeichen-Strings. Falls leer, wird nicht gesplittet. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const Methode

Teilt die Zeichenkette anhand eines Teilstrings. Derzeit wird nur ein Trennzeichen-Array von null oder einem Element unterstützt.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) von Trennzeichen-Strings. Falls leer, wird nicht gesplittet. |
| count | int | Maximale Anzahl von Elementen im Ergebnis-Array. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Optionen für das Aufteilen. |

### Rückgabewert

[Array](../../array/) von Teilstrings.

## Siehe auch

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)