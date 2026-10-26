---
title: HexUnescape()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert die angegebene hexadezimale Darstellung eines Zeichens in ein Zeichen.
type: docs
weight: 443
url: /de/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) Methode

Konvertiert die angegebene hexadezimale Darstellung eines Zeichens in ein Zeichen.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Ein String, der die hexadezimale Darstellung eines Zeichens enthält |
| index | **int32_t**\& | Die Position in **pattern**, an der die hexadezimale Darstellung eines Zeichens beginnt |

### Rückgabewert

Das Zeichen, das durch die hexadezimale Kodierung an Position **index** dargestellt wird. Ist das Zeichen an **index** nicht hexadezimal kodiert, wird das Zeichen an **index** zurückgegeben. Der Wert von **index** wird erhöht, sodass er auf das Zeichen nach dem zurückgegebenen Zeichen zeigt.

## Siehe auch

* Klasse [String](../../string/)
* Klasse [Uri](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)