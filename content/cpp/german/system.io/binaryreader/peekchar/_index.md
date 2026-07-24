---
title: PeekChar()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest ein einzelnes Zeichen aus dem Eingabestream, ohne den Lesekursor des Streams zu ändern.
type: docs
weight: 53
url: /de/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() Methode

Liest ein einzelnes Zeichen aus dem Eingabestream, ohne den Lesekursor des Streams zu ändern.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### Rückgabewert

Das gelesene Zeichen ist mit UTF-16 kodiert; wenn das gelesene Zeichen durch zwei Codepunkte in UTF-16 dargestellt wird, wird nur das hohe Surrogat zurückgegeben; wenn kein Zeichen gelesen wurde, wird -1 zurückgegeben

## Siehe auch

* Klasse [BinaryReader](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)