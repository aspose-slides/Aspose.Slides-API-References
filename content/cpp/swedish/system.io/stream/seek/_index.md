---
title: Seek()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in positionen för strömmen som representeras av det aktuella objektet.
type: docs
weight: 79
url: /sv/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) metod


Ställer in positionen för strömmen som representeras av det aktuella objektet.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | **int64_t** | Byteavståndet relativt en position som specificeras av **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Anger positionen från vilken och riktningen mot vilken avståndet beräknas |

### Returvärde

Den nya positionen för strömmen

## Se även

* Enum [SeekOrigin](../../seekorigin/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)