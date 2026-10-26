---
title: Write()
second_title: Aspose.Slides für C++ API Referenz
description: Schreibt das angegebene Zeichen in den Stream.
type: docs
weight: 40
url: /de/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) Methode

Schreibt das angegebene Zeichen in den Stream.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | char_t | Der zu schreibende Wert |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Zeichen aus dem angegebenen Zeichen-Array in den Stream.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Das Array, das die zu schreibenden Zeichen enthält |
| index | **int32_t** | Ein nullbasierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt |
| count | **int32_t** | Die Anzahl der Zeichen im zu schreibenden Teilbereich |

## StringWriter::Write(const String\&) Methode

Schreibt die angegebene Zeichenkette in den Stream.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Die zu schreibende Zeichenkette |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StringWriter](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)