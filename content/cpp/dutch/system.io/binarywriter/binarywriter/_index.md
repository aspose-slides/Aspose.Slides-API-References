---
title: BinaryWriter()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een instantie van de BinaryWriter klasse die gegevens naar de opgegeven stream schrijft met behulp van de opgegeven codering.
type: docs
weight: 1
url: /nl/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructor

Construeert een instantie van de [BinaryWriter](../) klasse die gegevens naar de opgegeven stream schrijft met behulp van de opgegeven codering.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | De uitvoerstream |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | De te gebruiken codering |
| leaveopen | **bool** | Specificeert of de stream **stream** open moet blijven (true) nadat het huidige object is verwijderd, of niet (false) |

## Zie ook

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)