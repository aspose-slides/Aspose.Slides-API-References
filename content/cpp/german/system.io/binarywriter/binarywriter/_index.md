---
title: BinaryWriter()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert eine Instanz der Klasse BinaryWriter, die Daten in den angegebenen Stream mit der angegebenen Codierung schreibt.
type: docs
weight: 1
url: /de/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) Konstruktor


Konstruiert eine Instanz der Klasse [BinaryWriter](../), die Daten in den angegebenen Stream mit der angegebenen Codierung schreibt.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Der Ausgabestream |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Codierung |
| leaveopen | **bool** | Gibt an, ob der Stream **stream** nach der Entsorgung des aktuellen Objekts offen bleiben soll (true) oder nicht (false) |

## Siehe auch

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [BinaryWriter](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)