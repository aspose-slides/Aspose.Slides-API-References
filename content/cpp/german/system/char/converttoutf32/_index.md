---
title: ConvertToUtf32()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert das angegebene UTF-16-Surrogatpaar in eine UTF-32-Codeeinheit.
type: docs
weight: 287
url: /de/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) Methode

Konvertiert das angegebene UTF-16-Surrogatpaar in eine UTF-32-Codeeinheit.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| highSurrogate | char_t | Der hohe Surrogatwert des zu konvertierenden UTF-16-Surrogatpaars |
| lowSurrogate | char_t | Der niedrige Surrogatwert des zu konvertierenden UTF-16-Surrogatpaars |

### Rückgabewert

Eine UTF-32-Codeeinheit, die durch die Konvertierung entsteht

## Char::ConvertToUtf32(const String\&, int) Methode

Konvertiert den Wert eines UTF-16-codierten Zeichens oder Surrogatpaars an einer angegebenen Position in einem String in eine UTF-32-Codeeinheit.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Ein String, der ein Zeichen oder Surrogatpaar enthält |
| index | int | Die Indexposition des Zeichens oder Surrogatpaars im angegebenen String |

### Rückgabewert

Eine UTF-32-Codeeinheit, die durch die Konvertierung entsteht

## Siehe auch

* Klasse [Char](../)
* Klasse [String](../../string/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)