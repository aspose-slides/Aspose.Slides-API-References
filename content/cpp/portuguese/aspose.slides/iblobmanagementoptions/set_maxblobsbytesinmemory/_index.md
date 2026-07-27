---
title: set_MaxBlobsBytesInMemory()
second_title: Referência da API Aspose.Slides for C++
description: Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode levar a um alto uso de memória. Use esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.
type: docs
weight: 92
url: /pt/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) method

Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode levar a um alto uso de memória. Use esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Observações

Este valor é ignorado se [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) for definido como false, pois a memória é então o único local de armazenamento disponível e limitar o uso de BLOBs na memória não tem efeito. 

O valor padrão é 629,145,600 bytes (600 MB). 

Você pode definir esta propriedade como zero, mas ainda será reservado uma pequena quantidade mínima de memória. 

## Veja também

* Classe [IBlobManagementOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)