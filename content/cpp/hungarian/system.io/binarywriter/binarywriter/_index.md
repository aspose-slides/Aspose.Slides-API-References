---
title: BinaryWriter()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy példányt a BinaryWriter osztályból, amely a megadott kódolás használatával adatot ír a megadott adatfolyamba.
type: docs
weight: 1
url: /hu/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) konstruktor

Létrehoz egy példányt a(z) [BinaryWriter](../) osztályból, amely a megadott kódolás használatával adatot ír a megadott adatfolyamba.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | A kimeneti adatfolyam |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó kódolás |
| leaveopen | **bool** | Megadja, hogy a **stream** adatfolyam nyitva maradjon-e (true) miután a jelenlegi objektum el lett dobva, vagy ne (false) |

## Lásd még

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [BinaryWriter](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)