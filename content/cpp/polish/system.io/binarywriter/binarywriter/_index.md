---
title: BinaryWriter()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy instancję klasy BinaryWriter, która zapisuje dane do określonego strumienia przy użyciu określonego kodowania.
type: docs
weight: 1
url: /pl/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) konstruktor

Tworzy instancję klasy [BinaryWriter](../), która zapisuje dane do określonego strumienia przy użyciu określonego kodowania.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Strumień wyjściowy |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie do użycia |
| leaveopen | **bool** | Określa, czy strumień **stream** ma pozostać otwarty (true) po usunięciu bieżącego obiektu, czy nie (false) |

## Zobacz także

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasa [BinaryWriter](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)