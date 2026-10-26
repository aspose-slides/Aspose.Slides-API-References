---
title: Seek()
second_title: Referência da API Aspose.Slides para C++
description: Define a posição do stream representado pelo objeto atual.
type: docs
weight: 79
url: /pt/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) method

Define a posição do stream representado pelo objeto atual.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| offset | **int64_t** | O deslocamento em bytes relativo a uma posição especificada por **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Especifica a posição a partir da qual e a direção em que o deslocamento é calculado |

### Valor de Retorno

A nova posição do stream

## Veja Também

* Enum [SeekOrigin](../../seekorigin/)
* Classe [Stream](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)