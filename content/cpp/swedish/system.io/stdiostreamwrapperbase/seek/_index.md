---
title: Seek()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in positionen för strömmen som representeras av det aktuella objektet.
type: docs
weight: 40
url: /sv/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek(int64_t, SeekOrigin) metod


Ställer in positionen för strömmen som representeras av det aktuella objektet.

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset | **int64_t** | Byteavståndet relativt en position som specificeras av **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specificerar positionen som offset beräknas från samt riktningen mot vilken den beräknas |

### Returvärde

Den nya positionen för strömmen

## Se även

* Enum [SeekOrigin](../../seekorigin/)
* Klass [STDIOStreamWrapperBase](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)