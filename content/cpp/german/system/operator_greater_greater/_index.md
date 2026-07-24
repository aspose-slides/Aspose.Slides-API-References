---
title: operator>>()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest einen String aus dem Eingabestream unter Verwendung der UTF-8-Kodierung.
type: docs
weight: 3004
url: /de/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) Funktion

Liest einen String aus dem Eingabestream unter Verwendung der UTF-8-Kodierung.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in | std::istream\& | Ein Eingabestream-Objekt (Instanziierung von **basic_ostream** mit **char**). |
| str | [String](../string/)\& | Ein String, der aus dem Eingabestream gelesen wird. |

### Rückgabewert

Ein Eingabestream, aus dem der String extrahiert wurde.

## System::operator>>(std::wistream\&, String\&) Funktion

Liest einen String aus dem Eingabestream.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in | std::wistream\& | Ein Eingabestream-Objekt (Instanziierung von **basic_ostream** mit ****wchar_t****). |
| str | [String](../string/)\& | Ein String, der aus dem Eingabestream gelesen wird. |

### Rückgabewert

Ein Eingabestream, aus dem der String extrahiert wurde.

## Siehe auch

* Klasse [String](../string/)
* Namensraum [System](../)
* Library [Aspose.Slides](../../)