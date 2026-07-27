---
title: set_MaxBlobsBytesInMemory()
second_title: Referência da API Aspose.Slides para C++
description: Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode gerar alto consumo de memória. Use esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.
type: docs
weight: 92
url: /pt/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) método


Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode gerar alto consumo de memória. Use esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Observações


Este valor é ignorado se [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) for definido como false, pois a memória será então o único local de armazenamento disponível e limitar o uso de BLOBs em memória não terá efeito. 

O valor padrão é 629,145,600 bytes (600 MB). 

Você pode definir esta propriedade como zero, mas ainda será reservada uma pequena quantidade mínima de memória. 
## Ver também

* Classe [BlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)