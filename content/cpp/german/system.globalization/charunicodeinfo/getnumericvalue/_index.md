---
title: GetNumericValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt den numerischen Wert, der dem angegebenen Zeichen zugeordnet ist.
type: docs
weight: 27
url: /de/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) Methode

Liefert den numerischen Wert, der dem angegebenen Zeichen zugeordnet ist.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ch | char16_t | Unicode-Zeichen. |

### Rückgabewert

Der numerische Wert oder -1, wenn das angegebene Zeichen kein numerisches Zeichen ist.

## CharUnicodeInfo::GetNumericValue(const String\&, int) Methode

Liefert den numerischen Wert, der dem Zeichen am angegebenen Index der Zeichenkette zugeordnet ist.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Die Zeichenkette, die das Unicode-Zeichen enthält. |
| index | int | Der Index des Unicode-Zeichens. |

### Rückgabewert

Der numerische Wert oder -1, wenn das angegebene Zeichen kein numerisches Zeichen ist.

## Siehe auch

* Klasse [CharUnicodeInfo](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Globalization](../../)
* Bibliothek [Aspose.Slides](../../../)