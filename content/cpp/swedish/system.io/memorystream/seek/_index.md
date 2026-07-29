---
title: Seek()
second_title: Aspose.Slides för C++ API-referens
description: Anger positionen för strömmen som representeras av det aktuella objektet.
type: docs
weight: 105
url: /sv/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) metod

Anger positionen för strömmen som representeras av det aktuella objektet.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | **int64_t** | Byteavståndet relativt en position som specificeras av **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specificerar positionen från vilken och riktningen mot vilken **offset** beräknas |

### Returvärde

Den nya positionen för strömmen

## Se även

* Enum [SeekOrigin](../../seekorigin/)
* Klass [MemoryStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)