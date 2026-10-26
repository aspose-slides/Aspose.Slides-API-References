---
title: Seek()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in positionen för strömmen som representeras av det aktuella objektet.
type: docs
weight: 209
url: /sv/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) metod

Ställer in positionen för strömmen som representeras av det aktuella objektet.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | **int64_t** | Byteavståndet relativt en position som specificeras av **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Anger positionen från vilken och riktningen mot vilken avståndet beräknas. |

### Returvärde

Den nya positionen för strömmen.

## Se även

* Enum [SeekOrigin](../../seekorigin/)
* Klass [FileStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)