---
title: Peek()
second_title: Aspose.Slides för C++ API-referens
description: Läser ett enskilt tecken från strömmen utan att ändra strömmens läsmarkör.
type: docs
weight: 27
url: /sv/system.io/streamreader/peek/
---
## StreamReader::Peek() metod


Läser ett enskilt tecken från strömmen utan att ändra strömmens läsläsare.

```cpp
virtual int System::IO::StreamReader::Peek() override
```


### Returvärde

Läs tecken kodad med UTF-16-kodning; om det lästa tecknet representeras av två kodpunkter i UTF-16-kodning returneras endast den högre surrogaten; om inget tecken lästes returneras -1

## Se även

* Klass [StreamReader](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)