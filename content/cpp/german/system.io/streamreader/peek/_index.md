---
title: Peek()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest ein einzelnes Zeichen aus dem Stream, ohne den Lesekursor des Streams zu ändern.
type: docs
weight: 27
url: /de/system.io/streamreader/peek/
---
## StreamReader::Peek() Methode

Liest ein einzelnes Zeichen aus dem Stream, ohne den Lesekursor des Streams zu ändern.

```cpp
virtual int System::IO::StreamReader::Peek() override
```

### Rückgabewert

Gelesenes Zeichen mit UTF-16 kodiert; wenn das gelesene Zeichen durch zwei Codepoints in UTF-16 kodiert ist, wird nur das hohe surragate zurückgegeben; wenn kein Zeichen gelesen wurde, wird -1 zurückgegeben

## Siehe auch

* Klasse [StreamReader](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)