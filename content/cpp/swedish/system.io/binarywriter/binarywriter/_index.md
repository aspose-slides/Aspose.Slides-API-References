---
title: BinaryWriter()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans av klassen BinaryWriter som skriver data till den angivna strömmen med den angivna kodningen.
type: docs
weight: 1
url: /sv/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) konstruktor


Skapar en instans av klassen [BinaryWriter](../) som skriver data till den angivna strömmen med den angivna kodningen.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Utdataströmmen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodningen som ska användas |
| leaveopen | **bool** | Anger om strömmen **stream** ska lämnas öppen (true) efter att det aktuella objektet har frigjorts eller inte (false) |

## Se också

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)