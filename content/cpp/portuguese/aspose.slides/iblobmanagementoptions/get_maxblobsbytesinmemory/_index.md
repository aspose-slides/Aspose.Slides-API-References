---
title: get_MaxBlobsBytesInMemory()
second_title: Referência da API Aspose.Slides para C++
description: Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido mecanismos alternativos (como arquivos temporários) são empregados. Manter os BLOBs na memória maximiza o desempenho, mas pode levar a um alto consumo de memória. Use esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.
type: docs
weight: 79
url: /pt/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() método

Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs são carregados na memória; somente quando esse limite é atingido mecanismos alternativos (como arquivos temporários) são empregados. Manter os BLOBs na memória maximiza o desempenho, mas pode levar a um alto uso de memória. Use esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Observações

Este valor é ignorado se [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) estiver definido como false, já que a memória será então o único local de armazenamento disponível e limitar o uso de BLOBs na memória não terá efeito. 

O valor padrão é 629,145,600 bytes (600 MB). 

Você pode definir esta propriedade como zero, mas uma pequena quantidade mínima de memória ainda será reservada. 

## Veja também

* Classe [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)