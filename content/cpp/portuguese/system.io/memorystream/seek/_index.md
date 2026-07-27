---
title: Seek()
second_title: Referência da API Aspose.Slides para C++
description: Define a posição do fluxo representado pelo objeto atual.
type: docs
weight: 105
url: /pt/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) método


Define a posição do fluxo representado pelo objeto atual.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| offset | **int64_t** | O deslocamento em bytes relativo a uma posição especificada por **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Especifica a posição a partir da qual e a direção para a qual o deslocamento é calculado |

### Valor de Retorno

A nova posição do fluxo

## Veja Também

* Enum [SeekOrigin](../../seekorigin/)
* Classe [MemoryStream](../)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)