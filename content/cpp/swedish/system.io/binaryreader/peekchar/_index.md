---
title: PeekChar()
second_title: Aspose.Slides för C++ API-referens
description: Läser ett enda tecken från inmatningsströmmen utan att ändra strömmens läsposition.
type: docs
weight: 53
url: /sv/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() metod

Läser ett enda tecken från inmatningsströmmen utan att ändra strömmens läsposition.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### Returvärde

Läst tecken kodad med UTF-16; om det lästa tecknet representeras av två kodpunkter i UTF-16-kodning returneras endast den högre surrogaten; om inget tecken lästes returneras -1.

## Se även

* Klass [BinaryReader](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)