---
title: Seek()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in positionen för strömmen som representeras av det aktuella objektet.
type: docs
weight: 79
url: /sv/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) metod


Ställer in positionen för strömmen som representeras av det aktuella objektet.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | int | Byteavståndet relativt en position som anges av **origin** |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | Anger positionen från vilken och riktningen mot vilken offset beräknas |

### Returvärde

Den nya positionen för strömmen

## Se även

* Enum [SeekOrigin](../../seekorigin/)
* Klass [BinaryWriter](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)