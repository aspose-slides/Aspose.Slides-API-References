---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory propriedade
Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs
            são carregados na memória; somente quando esse limite é alcançado são empregados mecanismos alternativos (como arquivos temporários)
            são empregados. Manter os BLOBs na memória maximiza o desempenho, mas pode levar a um alto uso de memória. Use
            esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.


### Observações

Esta propriedade é ignorada se [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pt/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) for definido como false, já que a memória é então
            o único local de armazenamento disponível e limitar o uso de BLOBs na memória não tem efeito.

### Definição:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Veja também
* classe [`BlobManagementOptions`](/slides/python-net/pt/aspose.slides/blobmanagementoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)