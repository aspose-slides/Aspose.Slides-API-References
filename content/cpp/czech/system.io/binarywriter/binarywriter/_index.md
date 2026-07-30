---
title: BinaryWriter()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří instanci třídy BinaryWriter, která zapisuje data do zadaného proudu pomocí zadaného kódování.
type: docs
weight: 1
url: /cs/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) konstruktor


Vytvoří instanci [BinaryWriter](../) třídy, která zapisuje data do zadaného proudu pomocí zadaného kódování.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Výstupní proud |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kódování, které se má použít |
| leaveopen | **bool** | Určuje, zda má být proud **stream** ponechán otevřený (true) po uvolnění současného objektu, nebo ne (false) |

## Viz také

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)