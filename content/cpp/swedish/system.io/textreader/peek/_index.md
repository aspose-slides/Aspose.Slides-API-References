---
title: Peek()
second_title: Aspose.Slides för C++ API-referens
description: Läser ett tecken från strömmen utan att ändra strömmens läsposition.
type: docs
weight: 27
url: /sv/system.io/textreader/peek/
---
## TextReader::Peek() metod


Läser ett tecken från strömmen utan att ändra strömmens läsposition.

```cpp
virtual int System::IO::TextReader::Peek()
```


### Returvärde

Läste tecken kodade med UTF-16; om det lästa tecknet representeras av två kodpunkter i UTF-16-kodning returneras endast den högre surrogaten; om inget tecken lästes returneras -1

## Se även

* Klass [TextReader](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)