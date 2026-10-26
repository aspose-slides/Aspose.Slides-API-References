---
title: Peek()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest ein einzelnes Zeichen aus dem Stream, ohne den Lesezeiger des Streams zu ändern.
type: docs
weight: 27
url: /de/system.io/textreader/peek/
---
## TextReader::Peek() Methode


Liest ein einzelnes Zeichen aus dem Stream, ohne den Lesezeiger des Streams zu ändern.

```cpp
virtual int System::IO::TextReader::Peek()
```


### Rückgabewert

Gelesenes Zeichen, codiert mit UTF-16; wenn das gelesene Zeichen durch zwei Codepunkte in UTF-16 dargestellt wird, wird nur das hohe Surrogat zurückgegeben; wenn kein Zeichen gelesen wurde, wird -1 zurückgegeben

## Siehe auch

* Klasse [TextReader](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)